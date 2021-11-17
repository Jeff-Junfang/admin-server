# 工程简介
admin server test

as nacos client;
integrate admin server starter;
config 
```
management:
  endpoints:
    web:
      exposure:
        include: '*'
#  endpoint:
#    health:
#      show-details: always
```
it can monitor all the nacos client via nacos

also, you can integrate Spring Security to protect you admin server
```
spring:
  security:
    user:
      name: admin
      password: admin
```