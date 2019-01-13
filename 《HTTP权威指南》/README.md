#  HTTP权威指南


## HTTP method

- 一些常见的HTTP方法：
    - GET
    - POST
    - PUT               添加
    - DELETE
    - HEAD              仅发送命名资源响应中的HTTP首部

## HTTP 状态码

- 一些常见的HTTP状态码：
    - 200               OK。文档正确返回
    - 302               Redirect(重定向)。到其他地方获取资源
    - 304               很多浏览器的 开发者工具 会发出额外的请求，以达到 304 的目的，这样可以把资源以本地缓存的形式展现给开发者。
    - 404               Not Found(没找到)。无法找到这个资源

## HTTP报文

- 报文分为请求报文合响应报文，报文包括起始行、首部字段合主体。
- ![报文实例图](https://github.com/Daibai/book-note/blob/master/%E3%80%8AHTTP%E6%9D%83%E5%A8%81%E6%8C%87%E5%8D%97%E3%80%8B/static/message.png)

## 连接

- 连接步骤：
    - 浏览器从URL中解析出服务器的主机名；
    - 浏览器将服务器的主机名转成服务器的IP地址；
    - 浏览器将端口（如果有的话）从URL中解析出来；
    - 浏览器建立一条与Web服务器的TCP连接；
    - 浏览器向服务器发送一条HTTP请求报文；
    - 服务器向浏览器发送一条HTTP响应报文；
    - 关闭连接，显示文档。

## URL

- URL语法 `<scheme>://<user>:<password>@<host>:<port>/<path>;<params>?<query>#<frag>`
    - scheme 方案，使用什么协议
    - 用户名和密码
    - 主机与端口
    - 路径
    - 参数
    - 查询字符串
    - 片段,"#"开头，使用见下图
    - ![报文实例图](https://github.com/Daibai/book-note/blob/master/%E3%80%8AHTTP%E6%9D%83%E5%A8%81%E6%8C%87%E5%8D%97%E3%80%8B/static/url%23.png)