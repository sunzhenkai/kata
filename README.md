# 简介

`kata` 相识自《代码整洁之道》，这里指每日用于上手的题目。

# 使用

```shell
$ ./kata
command [add|take|rm|show|quit] : [operation]
```

**操作**

- add
  - 添加题目，信息包括名称 `name` 和描述 `desc` 
  - 题目为一行，描述可多行，以单行 `...` 结束输入
  - 题目保存至同目录下 `data.json` 
- take
  - 从题库中随机获取题目，并打印
- rm
  - 移除题目
- show
  - 展示所有题目
- quit
  - 退出程序