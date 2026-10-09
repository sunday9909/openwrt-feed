        
        # 格式：copy_feed "GitHub仓库链接" "分支名(选填，留空则克隆默认分支)"
        
        # 1. Nikki 核心与插件（多包集成仓库，已支持深度扫描）
        copy_feed "https://github.com/nikkinikki-org/OpenWrt-nikki.git"
        
        # 2. sirpdboy 的定时任务与家长控制
        copy_feed "https://github.com/sirpdboy/luci-app-taskplan.git"
        copy_feed "https://github.com/sirpdboy/luci-app-parentcontrol.git"
        
        # 3. AirConnect 无线音频桥接
        copy_feed "https://github.com/sbwml/luci-app-airconnect.git"
        
        # 4. sirpdboy 的网络测速
        copy_feed "https://github.com/sirpdboy/netspeedtest.git"
        
        # 5. 网络唤醒加强版
        copy_feed "https://github.com/isalikai/luci-app-owq-wol.git"

        copy_feed "https://github.com/FUjr/QModem.git"

        copy_feed "https://github.com/qosmio/nss-packages.git"
