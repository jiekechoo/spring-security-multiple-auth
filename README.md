#本实例演示了spring security 多重认证（网页认证和httpBasic认证）

##1、网页认证适合于网页类应用；


##2、httpBasic认证适合API类（web service）应用；

###API保活访问采用cookie方式： curl http://localhost:8080/api/i/user/9 -H "Cookie:SESSION=5b55e933-7c68-4333-82e4-656d777d72a4"
