HTTP协议
-------
#### 什么是HTTP协议

  协议是指计算机通信网络中两台计算机之间进行通信所必须共同遵守的规定或规则，超文本传输协议(HTTP)是一种通信协议，它允许将超文本标记语言(HTML)文档从Web服务器传送到客户端的浏览器，目前我们使用的是HTTP/1.1 版本

  当我们打开浏览器，在地址栏中输入URL，然后我们就看到了网页。 原理是怎样的呢？
  
  实际上我们输入URL后，我们的浏览器给Web服务器发送了一个Request, Web服务器接到Request后进行处理，生成相应的Response，然后发送给浏览器， 浏览器解析Response中的HTML,这样我们就看到了网页

  我们的Request 有可能是经过了代理服务器，最后才到达Web服务器的。
  
  代理服务器就是网络信息的中转站，有什么功能呢？<br>
    1. 提高访问速度， 大多数的代理服务器都有缓存功能。<br>2. 突破限制，也就是翻墙了。<br>3. 隐藏身份。

  1XX---指示信息
  2XX---请求成功
  3XX---重定向
  4XX---客户端错误
  5XX---服务端错误
