🔵 本文简介

    数据备份  
    系统重装
    系统配置
    基础软件
    极品软件


🔵 数据备份

    装系统前想的再怎么仔细，肯定还是会漏掉的，而且是非常重要的文件！
    比如各种软件的配置文件！！！ 所以 timemachine 是必须的。

    你有 NAS 备份很简单，
    没有的话买个ssd 来备份！！ 平时还难当u 盘用，
    电脑连ssd 只要一根数据线就可以了！！！ 数据无价。



🔵 系统重装

    🔶 简介

        系统分两种 
        最新版系统可以直接在线通过网络安装，无需任何东西！
        老版本系统需要自己制作 USB 启动盘了。。。 麻烦。
        但是这里 karabiner 这个键盘神器只支持 10.11 
        虽然现在都出到 10.13 了 但是我还是决定重装10.11
        Mac 系统的版本选择 和 Win 差不多的， 
        Win 还是 win7 最经典，Mac 我认为是 10.11 最经典了
        加上苹果没了乔布斯。。。 不管是软件还是硬件质量普遍不行了！


    🔶 最新版本系统：

        开机 → ⌘ ＋ R 直接在线重装！

    🔶 老版本系统： 自己准备u 盘。。。
    
        ☉ 准备工作 
            • 8G ＋ U盘一个 
            • 老版本系统镜像
            • Mac 电脑（带系统的）
            ⚡︎ Win 也能制作 Mac 的USB 启动盘，但是麻烦。。。



        ★★★★★ 参考教程：http://www.iplaysoft.com/osx-yosemite-usb-install-drive.html


        ☉ 步骤简介
            不管制作什么版本Mac USB 启动盘， 步骤都是一样！ 
            大概就是下载系统镜像 → 解压 → 格式化 u盘 → 用命令把镜像写到U盘 
            ⚡︎ 命令就是重点！  你要改到无法就是 系统名字  和 u盘名字。

        ☉ 命令
            sudo /Applications/Install\ OS\ X\ El\ Capitan.app/Contents/Resources/createinstallmedia --volume /Volumes/iPlaySoft --applicationpath /Applications/Install\ OS\ X\ El\ Capitan.app --nointeraction

            回车后，系统会提示你输入管理员密码，接下来就是等待系统开始制作启动盘了。这时，命令执行中你会陆续看到类似以下的信息：
            Erasing Disk: 0%... 10%... 20%... 30%...100%...
            Copying installer files to disk...
            Copy complete.
            Making disk bootable...
            Copying boot files...
            Copy complete.
            Done.
            当你看到最后有 「Copy complete」和「Done」 字样出现就是表示启动盘已经制作完成





🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶  🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶

🔵 macOS 系统初始设置

🔶 触控板 

    ● 轻点变单击 
    ● 三指拖放 （设置 辅助功能 》 鼠标/触控板 〉启用拖移 》 三指拖移 


🔶 输入法快捷键： 
    
    设置 → 键盘 → 快捷键 → 输入来源 → 打勾 → 设置快捷键 ctrl ＋ 空格


🔶 Finder 
    默认显示全部文件 脑子怎么想的！ fuck 。。  
    改为默认显示桌面文件。  
    finder 设置 




🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶  🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶

＃ 软件

    推荐网站1（国内）： https://www.waitsun.com
    推荐网站2（国内）： xclient。info
    推荐网站3（国外）： appked




🔵 xcode 必装  Apple Store







🔵 翻墙软件 

    SS 最简单。 
    Specht Lite 配置要点功夫
    Surge 最好但是太贵，破解版问题多
    

    ssx  https://github.com/shadowsocks/ShadowsocksX-NG 

    specht lite 官方下载   https://github.com/zhuhaow/SpechtLite/releases
        配置下载  https://github.com/HoonHwang/SpechtLiteConf
        教程：http://xclient.info/s/spechtlite.html?_=c4302fa9c19438bae7c00da40c26c69a


🔵 谷歌浏览器 （书签）


🔵 窗口控制软件（ WIN 左右自动分屏 ）  →BetterSnapTool

🔵 istat 6 → 系统监控


🔵 Alfred 3

    官网下载： https://www.alfredapp.com/
    正版账号。  126 邮箱里面




🔵 VSCode    https://code.visualstudio.com/docs/?dv=osx


🔵 Github  Tower（收费） ／ github desktop （免费）
    Github 直接登陆就可以了。  
    Tower  要登陆配置：github 账户设置 → Developer settings → 生成 personal access token




# gce 设置ssh 证书

1. 密钥生成 ssh-keygen -t rsa
2. 密钥位置 ~/.ssh/id_rsa.pub
3. 上传   gce 元数据 添加 ssh 密钥   就是 cat ~/.ssh/id_rsa.pub   
4. ssh -p 2190 root@35.194.128.92






🔵 karabiner & seil
Karibiner 只支持 10.11   10.12+ 的功能限制非常严重！

karabiner 10.22下载 ： https://pqrs.org/osx/karabiner/

Seil 下载 https://download.freedownloadmanager.org/Mac-OS/Seil/FREE-12.1.html




使用：
阿斯顿 asdf大师傅  水电费叫阿道夫 


＃ ShowyEdge
输入法切换是个头疼的事情！  特别是标点符号。  
用了这个 就能非常明显的判断当前是什么输入法。 而不用去看角落的小图标了。。。。
没啥大用， 但是就是好用。。。
https://pqrs.org/osx/ShowyEdge/

默认 英文是正常的。 换成中文就是红色。  程序员还是输入英文较多的。。



💗
seil 设置 

把 cap 键 变成 ctrl 键！！！ 
自带的键盘，cap 几乎用不到的！ ctrl 是常用的。
不需任何软件。 直接九能改！


如果要把 cap 变成别的键  就要 seil 了。 

系统设置  键盘  修改键 。。。



使用”default”设置。主要是设置CapsLock键为Control键：
禁用系统的CapsLock键
系统偏好设置–>键盘–>修饰键，设置CapsLock为无操作
通过Seil设置CapsLock为F19
下载安装Seil，选择Change the caps lock key为80（F19）
设置F19为Escape和Control
Custom shortcuts->F19 to Escape and Control。这样点击此键，就是ESC，组合其他键就是

详细参考设置：  http://www.jianshu.com/p/30a95c0727a9




🔵 Keyboard Maestro 8.0 

🔶 表情符号快捷键  
    ；fs → 🔶
    ；fb → 🔵
    。。。。。。



🔶 软件快捷键 （Vscode）

    ⌥｀ → ⌘｀ 也就是打开内置的终端。


🔶 系统快捷键 
    ⌘ D → ⌘ Delete 这样左手就能直接删除文件了， 英文右手一般控制触摸板的，按 ⌘ Delete 不方便










🔵 brew  
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"


🔵 基础命令安装 
    如 wget 

    brew install wget





🔵 iTerm ＋ on-my-zsh 

iTerm2 要手动下载


on-my-zsh 安装
wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O - | sh







🔵 安装 nmap  
brew install nmap 





`
｀

