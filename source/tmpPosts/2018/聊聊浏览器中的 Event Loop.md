---
title: 聊聊浏览器中的 Event Loop
date: 2018-04-15
---

### 前言
对于 nodejs 开发和前端开发 Event Loop 这个词再熟悉不过了，

- [JavaScript 运行机制详解：再谈Event Loop](http://www.ruanyifeng.com/blog/2014/10/event-loop.html)
- [【朴灵评注】JavaScript 运行机制详解：再谈Event Loop](https://blog.csdn.net/lin_credible/article/details/40143961)
- [从event loop规范探究javaScript异步及浏览器更新渲染时机](https://github.com/aooy/blog/issues/5)
- [Tasks, microtasks, queues and schedules](https://jakearchibald.com/2015/tasks-microtasks-queues-and-schedules/)
- [event-loops](https://html.spec.whatwg.org/multipage/webappapis.html#event-loops)
- [html5 event-loops](https://www.w3.org/TR/html5/webappapis.html#event-loops)