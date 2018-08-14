# rfc - 研究rfc协议，并对这些协议进行基本的golang实现

## 1. RFC 4226 - HOTP
协议地址: [rfc4226](https://tools.ietf.org/html/rfc4226)

## 2. RFC 6238 - TOTP
协议地址: [rfc6238](https://tools.ietf.org/html/rfc6238)

> 以上两个协议是关于TFA的(two-factor authentication)，描述了一种生成并验证一次性密码的算法
>
> 参考实现为 [pquerna/otp](https://github.com/pquerna/otp)


## 3. RFC 6445 - WebSocket
协议地址: [rfc6445](https://tools.ietf.org/html/rfc6445)

> websocket就不用多说了，web开发的同学应该都听说过的一个协议。
> 
> 参考实现为 [gorilla/websocket](https://github.com/gorilla/websocket)

## 4. RFC 5321 - SMTP
协议地址: [rfc5321](https://tools.ietf.org/html/rfc5321)

> smtp是发送邮件协议
> 
> 参考实现为 [mhale/smtpd](https://github.com/mhale/smtpd)

## 5. RFC 3501 - IMAP4rev1
协议地址: [rfc3501](https://tools.ietf.org/html/rfc3501)


> imap 原指交互式邮件访问协议(),后来改称为互联网消息访问协议(Internet Message Access Protocol)
> 主要规定了邮件客户端如何从邮件服务器获取邮件
>
> 参考实现为 [emersion/go-imap](https://github.com/emersion/go-imap)