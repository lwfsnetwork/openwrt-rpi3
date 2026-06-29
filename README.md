使用方式

Fork本项目
Fork后，去 Actions 頁面點 Run workflow 即可開始編譯。
編譯完成後下載 Artifacts 中的 .img.gz 檔案，用 balenaEtcher 燒到 SD 卡。

編譯後效果

後台 IP：192.168.192.254
密碼：Mz2156822
主機名：iRouter
語言：簡體中文
主題：Bootstrap
Overlay 擴容到 4096M
旁路由模式（DHCP 已忽略）
已包含插件：PassWall、luci-app-ddns、luci-app-qbittorrent、luci-app-ttyd、自动挂载USB/硬盘、Docker
