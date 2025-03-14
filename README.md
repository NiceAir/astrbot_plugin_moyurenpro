# 摸鱼日历

![Image text](https://github.com/DuBwTf/astrbot_plugin_moyurenpro/blob/ae88056ae5c3d57ed41059e4a533faa24fd56100/moyu.png
)

由原作者[DuBwTf](https://github.com/DuBwTf/astrbot_plugin_moyurenpro) 项目魔改而成

# 支持

支持权限控制,支持自定义时间时区，自定义api,支持立即发送，节假日定时发送。需安装第三方库chinese_calendar，点击帮助查看安装方法。  # 插件简短描述


help: 输入/set_manager 设置管理者，只有管理者能设置摸鱼日历的配置，输入 /set_time 定时时间（格式：HH:MM或HHMM） 设置时间，输入 /reset_time 重置时间
     输入 摸鱼日历 立即发送， 该指令可由所有人触发

需安装第三方库[chinese_calendar](https://github.com/LKI/chinese-calendar)
```
docker exec -it astrbot /bin/bash #docker部署进入astrbot容器，运行bash进行安装

pip install chinesecalendar
```
