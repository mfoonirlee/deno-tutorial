# 开发日志

## 20200609

> 遇到问题不要慌，放好心态，逐步排查，然后搜重点，实在不行社区里问问题。

* 合并 (#4)[https://github.com/hylerrix/deno-tutorial/pull/4] PR。
* 三小时尝试构建 pagic，解决了如下安装时的问题：
  * 报错 `error: Uncaught Http: error sending request for url (https://raw.githubusercontent.com/pillarjs/path-to-regexp/v6.1.0/src/index.ts): error trying to connect: tcp connect error: Connection refused (os error 61)`：给 `/etc/hosts` 文件增加 `199.232.68.133 raw.githubusercontent.com` 即可。
  * 报错 `TS2345 [ERROR]: Argument of type '{ type: string; }' is not assignable to parameter of type 'string'.`：升级 Deno 版本到 v1.0.5 即可。

## 20200513~20200531

* 值 Deno v1.0 发布之际开源本电子书。
* 这段时间创作了两篇文章并授权翻译了三篇文章。