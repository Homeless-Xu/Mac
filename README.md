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


🔵 输入法设置

    自带的输入法非常不好用， 就是因为标点符号！ 
    IT人员肯定喜欢 在中文输入法下用英文标点！ 
    怎么办呢！只能换输入法了。有三个选择。。。
    • 自带中文输入法：➜ 按Cap 就变成英文模式！！！ 再输标点 就会变成变成英文输入法
    • 搜狗输入法：➜ 慢！卡。。。 
    • 百度输入法：➜ 虽然很讨厌百度。。。 但是还是试试看吧。 某些人说这个蛮好用的。。
    • 鼠须管： ➜ 配置麻烦！！ 非常麻烦。。


    🔶 Cap 键

        在因为输入法下按Cap键 ➜ 大写模式
        在中文输入法下按Cap键 ➜ 相当于英文输入法！标点也是英文的. 要输入大写英文 按下shift就行. 
        中文输入法下的 Cap 的英文模式 和 直接 切换英文输入法 也就是按一个键 或则 按两个键的区别。


    🔶 百度输入法

        ☉ 设置

            • 中文时使用英文标点
            • 启用模糊拼音
            • 取消状态条
            • 候选词: 9 
            • 安静模式( 在某些软件 强制用英文! 比如 Alfred )


        ☉ 使用 

            • shift 可以直接用来切换中英文! 


    🔶 ShowyEdge 软件

        百度输入法有英文模式, 系统自己也有英文输入法. 
        一般来说,直接使用百度输入法就可以了,但是毕竟是苹果的系统,肯定情况下默认会是Mac的英文输入法的.
        怎么判断当前到底是什么输入法就比较重要了! 不然电脑用着不爽!

        用 ShowyEdge 这个软件 就能非常明显的判断当前是什么输入法。 而不用去看角落的小图标了。。。。
        这软件会在屏幕顶部显示一条颜色条, 高度 以及 然颜色自己可以改.

        没啥大用， 但是就是好用。。。    https://pqrs.org/osx/ShowyEdge/
        系统 英文 输入法: 无色
        系统 中文 输入法: 红色
        百度 中文 输入法: 灰色

        ☉ 自定义颜色

            百度输入法的时候 无色.
            系统英文输入法时 红色.


    🔶 Emoji 快捷键: ⌘ ⇧ 空格





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

🔵 盗版软件资源

    ★★★★★    推荐网站1（国内）： https://www.waitsun.com
    ★★★★      推荐网站2（国内）： xclient。info
    ★★★★★    推荐网站3（国外）： appked




🔵 xcode 必装  Apple Store







🔵 翻墙软件 

    🔶 临时翻墙帐号！ 

        23.105.192.96   443
        加密：  chacha20 
        密码 UUrtCi

    🔶 客户端选择

        • SS → 最简单， 性能一般般
        • Specht Lite → 配置要点功夫， 性能好
        • Surge → 性能最好！ 但是太贵了！ 几乎没有破解！ 
        

        ssx 官方下载：   https://github.com/shadowsocks/ShadowsocksX-NG 

        specht lite 官方下载   https://github.com/zhuhaow/SpechtLite/releases
            配置下载  https://github.com/HoonHwang/SpechtLiteConf
            教程：http://xclient.info/s/spechtlite.html?_=c4302fa9c19438bae7c00da40c26c69a



🔵 谷歌浏览器 （书签）


🔵 窗口控制软件 BetterSnapTool

    🔶 跨屏问题

        安装好就能左右 以及 四角的自动调整窗口大小了。
        但是有个小问题。 你的窗口可能会到另外到界面去。
        这个问题其实是Mac系统到问题，解决方法只能用下面命令增加延迟（2秒）。
        defaults write com.apple.dock workspaces-edge-delay -float 2.0; killall Dock

    🔶 快捷键设置 
        BetterSnampTool → 设置 → keyboard shortcuts 

        ⌥ ， 左下角
        ⌥ 。 右下角
        ⌥ o 左上角
        ⌥ p 右上角

        ⌥ H 左半屏
        ⌥ L 右半屏
        ⌥ J 下半屏
        ⌥ K 上半屏






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

🔶 简介

    Karibiner 这个神奇只支持 10.11   10.12+ 的功能限制非常严重！
    但是有几个小的键盘设置 需要配合 seil 才能完成。 

    karabiner 10.22下载 ： https://pqrs.org/osx/karabiner/
    Seil 下载 https://download.freedownloadmanager.org/Mac-OS/Seil/FREE-12.1.html


🔶 Seil： Cap → Ctrl ＋ Esc 

    把 Cap 键 变成 Ctrl ＋ Esc 键！！！ 
    cap 几乎用不到的！ ctrl 是常用的。
    Mac 内置键盘，Cap 键却占据极好的位置，而且还那么大。
    不好好用就浪费了，所以才会有那么多人要把这个变成 Ctrl 键盘。
    再厉害点的，同时把这个键变成两个键： Ctrl 和 ESC
    也就是说 组合键的时候 这个Cap会变成Ctrl， 单按的时候是Esc

    如果你只要把 Cap 键和 Ctrl 键 互换，而不要那个 Esc 功能，那么不需任何软件。 
    Mac 10.11 直接就能改！系统偏好设置–>键盘–>修饰键，设置Cap Ctrl 互换

    如果要把 Cap 变成 Ctrl ＋ Esc  就要用 seil 了。 

    1. 禁用系统的CapsLock键
        系统偏好设置 ➜ 键盘 ➜ 修饰键 ➜ CapsLock 设置为 No Acton

    2. Seil设置CapsLock为F19
        下载安装Seil ➜ Change the caps lock key 的值改为80（F19）

    3. Karabiner 配置修改

        打开karabiner,在「Misc & Uninstall」中点击「Open private.xml」，会弹出来一个文档。
        打开该文档，将下面的代码替换进去：

        <?xml version="1.0"?>
        <root>
        <item>
        <name>F19 To Control</name>
        <appendix>F19, send Control</appendix>
        <identifier>private.hyperspace2Control</identifier>
        <autogen>
        --KeyToKey--
        KeyCode::F19, 
        KeyCode::CONTROL_L
        </autogen>
        </item>
        </root>


    4. Karabiner 设置F19为Escape和Control
        回到「Change Key」中点击「ReloadXML」，就会看到自定义的名为F19 To Control的映射选项.勾选即完成映射.


    详细图文参考设置：  http://www.jianshu.com/p/30a95c0727a9



🔶 Karabiner 方向键

    Mac 自带的方向键非常难按啊！
    右手要移动非常大的距离才能按到方向键。Karabiner 就可以帮你结局这个问题。
    之所以选择10.11 而不是 10.12 就是为了 Karabiner 的方向键这个功能。
    我喜欢把 S 当成方向修饰键！ 按下S 再按下 HJKL 就对应 上下左右！
    要实现这个功能 非常简单。也就是 Karabiner 里所谓的 VI Mode 勾选就可以了。






















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

    ☉ iTerm2 手动下载

    ☉ on-my-zsh 安装
        wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O - | sh



🔵 安装 nmap  
    brew install nmap 


🔵 安装 MTR 
 pkg 安装包




🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶  🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶 🔶




