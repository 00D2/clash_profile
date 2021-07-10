# clash_profile
Clash简单易用的配置文件。下载配置文件后，仅需修改ss或vmess的信息，并在proxy-groups中调用后，即可使用。
本配置文件仅保留了ss及vmess两种协议支持，如需其他协议的配置方法，可参考大佬的配置模板[@Hackl0us](https://github.com/Hackl0us/SS-Rule-Snippet/blob/master/LAZY_RULES/Clash_Premium.yaml)

# 致谢
该配置文件由下面两位大佬共享的文件改写而成，方便像我这样的小白使用。向大佬致谢！！！
两位大佬还有surge、shadowrocket等规则，安利！！！
[@Loyalsoldier](https://github.com/Loyalsoldier/)
[@Hackl0us](https://github.com/Hackl0us)

#使用说明
## Windows使用说明
1. 下载clash_profile.yaml文件；
2. 将下载得到的文件，放到$HOME/.config/clash/profiles/文件夹下；此处的$HOME是C盘-用户-“对应的用户文件夹”
3. 使用文本编辑器修改文件，修改其中proxies下的ss或vmess服务器信息；
4. 修改proxy-groups中的proxies名称（为第3步创建的ss或vmess服务器name）；
5. 完成配置修改后，在Dashboard-Profiles-Import，选择刚才的文件；
6. 在Dashboard-Profiles下，点击刚才导入的文件，文件前面显示为绿色，则表示正在使用该配置文件；
7. 启用系统代理，畅享互联网。

##macOS使用说明

