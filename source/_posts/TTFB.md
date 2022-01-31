---
title: TTFB
date: 2022-01-24 23:01:15
tags:
---

第一字节时间(Time To First Byte), 是指从**浏览器请求页面**到从**浏览器接收到来自服务器发送的信息的第一个字节**的时间。这一次包括DNS查找和使用(三次)TCP握手和SSL握手建立连接的时间(如果请求是通过https发出的)

> TTFB = responseStart - requestStart

衡量标准

0-75ms 完美
75-200ms 理想
200-500ms 虽不足亦不远矣
\>500ms 有问题


