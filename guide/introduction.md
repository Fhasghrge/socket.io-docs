> 这个指南中，我们将创建一个基本的聊天应用。它几乎不需要node.js 或 socket.io之前的知识，因此它是所有同等知识水平用户的理想选择。

- `traditionally 传统，一直以来`
- `involves 涉及`
- `polling 投票、轮询`

## 介绍

用流行的web应用栈比如LAMP(PHP)去编写一个聊天应用程序一直非常困难，它涉及到轮询服务器以进行更改，跟踪时间戳，并且应该会慢得很多。

传统上，socket 是大多数实时聊天系统所构建的解决方案，在客户端与服务端之间提供双向通信通道。

这意味着服务器可以将消息推送到客户端，每当编写聊天消息时，其做法是服务器获取消息，并将其推送到所有连接着的客户端。