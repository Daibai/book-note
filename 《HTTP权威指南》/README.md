#  HTTP权威指南


## HTTP method

- 一些常见的HTTP方法
    - GET
    - POST
    - PUT               添加
    - DELETE
    - HEAD              仅发送命名资源响应中的HTTP首部

## HTTP 状态码

- 一些常见的HTTP状态码
    - 200               OK。文档正确返回
    - 302               Redirect(重定向)。到其他地方获取资源
    - 304               很多浏览器的 开发者工具 会发出额外的请求，以达到 304 的目的，这样可以把资源以本地缓存的形式展现给开发者。
    - 404               Not Found(没找到)。无法找到这个资源

## HTTP报文

- 报文分为请求报文合响应报文，报文包括起始行、首部字段合主体。
- ![报文实例图](https://github.com/Daibai/book-note/blob/master/%E3%80%8AHTTP%E6%9D%83%E5%A8%81%E6%8C%87%E5%8D%97%E3%80%8B/static/message.png)

