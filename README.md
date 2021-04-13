# Demo.Jwt
.netcore 3.1 
看了demo有以下几点疑问:
1.使用太死板,需要在action里添加特性Authorize来启用jwt验证
2.多用户,多角色不适用
3.jwt等同于明文传输,意义在哪?
4.与传统的 cookie+session的区别在哪? 换个地方传,换个方式放服务端也叫区别?  jwt服务端重启还是会引起过期,实际过期时间没到
5.如果因为微服务的问题,可以采用 cookie+session+redis来验证
6.jwt的过期之后需要重新获取新的token, session可以自动延期,还能修改更长时效
7.
