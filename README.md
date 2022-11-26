# ATBot
# 注意！此存库已转移到团队存库
# https://github.com/AxT-Team/ATBot
基于Mirai-native的CQ查询插件（使用Mirai框架加载）<br>

## 查询功能如下
- MinecraftServer<br>
 拥有IP白名单系统，API可自定义（默认为https://api.imlazy.ink ），可以查询java和基岩<br>
 使用方法:/sv [IP] {端口}（端口默认25565）
- HypixelBanned<br> 
使用的Hypixel官方API接口（https://api.hypixel.net ），可查询客服Ban和DogBan<br>
使用方法:/hypban
- ICP备案查询（未实现）
- Ping延迟查询（未实现）
- Whois域名查询（v1.1.0版本已更新）

## 其他功能如下
- 实时查看CPU和内存使用情况
- 记录群聊和私聊的聊天记录到log文件夹
- 计算接收和发送消息量（发送量只能计算当前插件内功能使用时的消息）
- 自定义帮助命令和菜单排版（默认/help）
- 通过发送/atinfo查询机器人的当前所有情况信息<br>
（CPU占用，内存占用，发送消息数量，接收消息数量，运行时长）
- 收到好友添加/群邀请会私聊给设置的主人QQ

## 使用指令如下
- /atinfo - 查询机器人的当前所有情况信息
- /sv [IP] {端口} - 查询MinecraftServer信息<br>
附属指令:<br>
IP添加 [IP] - 添加白名单IP<br>
atiplist - 刷新白名单IP并发送出来<br>

- /help（默认） - 菜单命令
- /hypban - 查询HypixelBanned数量情况

## 后台示例图
![alt text](https://s1.ax1x.com/2022/08/31/v4zSL6.png)
