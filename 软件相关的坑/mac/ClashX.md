# MacOS ClashX设置修改代理端口教程

ClashX>配置>打开本地配置文件夹，找到“config.yaml”打开编辑。

> # (HTTP and SOCKS5 in one port)
> 
>   
> 
> mixed-port: 7890             （混合代理端口）
> 
>   
> 
> socks-port: 7891              （Socks5 代理端口）
> 
>   
> 
> port: 7892                         （HTTP 代理端口）
> 
>   
> 
> # RESTful API for clash
> 
>   
> 
> external-controller: 127.0.0.1:7893   （外部控制设置）
> 
>   
> 
> allow-lan: false
> 
>   
> 
> mode: rule
> 
>   
> 
> log-level: warning

根据实际需要修改所需端口保存。

退出ClashX重启打开即可。