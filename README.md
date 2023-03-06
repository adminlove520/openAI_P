# wechatbot
项目基于[openwechat](https://github.com/eatmoreapple/openwechat)
开发
###目前实现了以下功能
 + 群聊@回复
 + 私聊回复
 + 自动通过回复
 
# 注册openai
chatGPT注册可以参考[这里](https://juejin.cn/post/7173447848292253704)

# 安装使用
````
# 获取项目
git clone https://github.com/869413421/wechatbot.git

# 进入项目目录
cd wechatbot

# 复制配置文件
copy config.dev.json config.json

# 启动项目
go run main.go

启动前需替换config中的api_key

# TODOList

### Wechat更新
2023-2-27 22:38:48
Tencent更新策略：微信扫码登录cookie过期，导致storge.json的cookie过期，从而服务down;
