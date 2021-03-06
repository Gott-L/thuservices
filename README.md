# 清华常用信息/服务汇总

## 快速选课入口

[选课登录（校内或 SSLVPN）（选课时段内有效）](http://zhjwxk.cic.tsinghua.edu.cn/xklogin.do)

## 文件内容
- [info.md](info.md)
    - INFO重要信息集合
        - 校历
            - 2019-2020学年 春夏
            - 2020-2021学年 
        - 本科专业培养方案
        - 学校宣传资料
        - 选课时间表
        - 选课快捷方式
        - 选课系统相关说明
        - 期末考试时间/地点查询
        - 历年本科生开课目录
        - 清华大学迎新系统
        - 注册标志（用于学生火车票）
        - 校内校车
        - 校内地图
        - 清华大学调查问卷系统
- [utils.md](utils.md)
    - 一些脚本和工具
        - 一键评教
        - 选课冲突标记
        - INFO 网络学堂 Telegram 消息推送
        - 全校洗衣机状态
            - 全校洗衣机状态 - iOS 快捷方式
            - 全校洗衣机状态 - Telegram Bot 二哈
            - 洗衣监控与提醒 - 微信小程序
        - INFO GPA 计算器
        - 学堂在线视频自动播放
        - 学堂在线字幕下载器
        - 清华教学参考书爬取
        - 课程地点分享
        - 清华大学计算机系课程攻略
        - 校园网认证工具汇总
        - INFO/网络学堂 APP/插件
- [services.md](services.md)
    - 清华服务使用指北（主要面向 Linux 用户）
        - SSLVPN
        - 上网认证
            - 校园网基础知识
            - 命令行认证 自动认证
                - 命令行认证
                - 自动认证
            - 远端服务器代认证
            - 远端服务器网页认证
            - Tsinghua-Secure
            - Tsinghua-Secure 仅校内登录方式
        - 校园网特性讨论
            - 二层隔离/邻居发现隔离
                - IPv4
                - IPv6
            - 低端口阻断
            - 动态 IP
                - IPv6 静态后缀或短 IPv6 地址
            - 不符合 RFC 的 DHCP
        - 清华云盘
            - 魔改 Terminal 客户端
        - ISATAP 
            - 获取IPv6挂PT
        - WIN 10 激活

## 知道某个重要信息，但repo中未列出？

欢迎贡献！请 PR！

需要注意的是本 repo 中使用了 pre-commit hook，请安装，并在有 bash 与 python3 的环境中
进行 commit。

在 pre-commit hook 的作用下，README.md 是自动生成的，故如果需要在 README.md 中修改，
请在 aux 文件夹下进行。

由于 Windows 文件系统的限制，文件夹名不能为 aux，请在非Windows环境（WSL也可以）下克隆该项目。
