# 解决启动 Parallels Desktop 之后 macOS 没声音的问题

1. 在 Parallels Desktop 的控制中心，进入对应系统配置页面。
2. 打开**「硬件 — CPU 与内存 — 高级」**选项：
3. 将虚拟机监控程序修改为**「Apple」**，并保存。
4.   打开系统**「终端 Terminal」**软件，并执行以下命令：
```shell
$ sudo launchctl stop com.apple.audio.coreaudiod && sudo launchctl start com.apple.audio.coreaudiod
```
>若系统版本低于 macOS Catalina 10.15.3，请使用 `kill coreaudiod` 命令。

