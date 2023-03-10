## 《UNIX/Linux系统管理手册》（第五版 2017）

这里收集了第五版英文版，以及第四版中文版。内容太多，中文版分成6个文件。

第五版去掉了上一版的 Solaris, HP-UX, and AIX, 只保留 Debian, Ubuntu, RHEL/CentOS，以及 FreeBSD。

下面是台湾出的第五版中文版目录：

    目录

    第一部分　基礎管理

    第1章　從哪入手 3

    1.1　系統管理員的基本任務 3
    1.2　建議的知識背景 5
    1.3　Linux發行版 6
    1.4　本書中用到的示例系統 7
    1.5　寫法與印刷約定 9
    1.6　單位 10
    1.7　手冊頁和其他聯機文檔 11
    1.8　其他權威文檔 12
    1.9　其他信息源 13
    1.10　如何查找及安裝軟件 14
    1.11　選擇托管 18
    1.12　專業及相鄰學科 19
    
    第2章　引導與系統管理守護進程 21

    2.1　引導過程概覽 21
    2.2　系統固件 22
    2.3　引導裝載程序 24
    2.4　GRUB 25
    2.5　FreeBSD引導過程 27
    2.6　系統管理守護進程 29
    2.7　systemd詳解 31
    2.8　FreeBSD init與啟動腳本 41
    2.9　重新引導與關機 42
    2.10　系統無法引導的應對策略 43
    
    第3章　訪問控制與超級權限 47

    3.1　標準UNIX訪問控制 47
    3.2　管理root賬戶 50
    3.3　標準訪問控制模型的擴展 57
    3.4　現代訪問控制 59
    
    第4章　進程控制 64

    4.1　進程的組成 64
    4.2　進程的生命周期 66
    4.3　ps：監視進程 70
    4.4　使用top動態監視進程 72
    4.5　nice與renice：修改調度優先級 73
    4.6　/proc文件系統 74
    4.7　strace與truss：跟蹤信號和系統調用 75
    4.8　失控進程 77
    4.9　周期性進程 78
    
    第5章　文件系統 86

    5.1　路徑名 87
    5.2　文件系統的掛載與卸載 87
    5.3　文件樹的組織 89
    5.4　文件類型 91
    5.5　文件屬性 95
    5.6　訪問控制列表 101
    
    第6章　軟件的安裝與管理 110

    6.1　操作系統安裝 110
    6.2　軟件包管理 117
    6.3　Linux軟件包管理系統 117
    6.4　Linux高層軟件包管理系統 119
    6.5　FreeBSD軟件管理 125
    6.6　軟件的本地化與配置 128
    
    第7章　腳本編程與shell 130

    7.1　腳本化的哲學 130
    7.2　shell基礎 134
    7.3　sh腳本編程 141
    7.4　正則表達式 150
    7.5　Python編程 154
    7.6　Ruby編程 160
    7.7　Python和Ruby的庫與環境管理 165
    7.8　使用Git實現版本控制 169
    
    第8章　用戶管理 174

    8.1　賬戶機制 175
    8.2　/etc/passwd文件 175
    8.3　Linux的/etc/shadow文件 179
    8.4　FreeBSD的/etc/master.passwd文件與/etc/login.conf文件 180
    8.5　/etc/group文件 182
    8.6　手動添加用戶 183
    8.7　用腳本添加用戶：useradd、adduser、newusers 187
    8.8　安全刪除用戶的賬戶及其文件 189
    8.9　禁止登錄 190
    8.10　使用PAM降低風險 191
    8.11　集中式賬戶管理 191
    
    第9章　雲計算 193

    9.1　雲 194
    9.2　雲平臺的選擇 195
    9.3　雲服務基礎 197
    9.4　雲：各種平臺上的VPS快速入門 202
    9.5　成本控制 207
    
    第10章　日誌 210

    10.1　日誌位置 212
    10.2　systemd journal 214
    10.3　syslog 216
    10.4　內核與引導期間的日誌記錄 228
    10.5　日誌文件的管理與輪替 229
    10.6　管理大規模日誌 230
    10.7　日誌記錄策略 232
    
    第11章　驅動程序與內核 233

    11.1　內核相關的日常事務 234
    11.2　內核版本編號 234
    11.3　設備及其驅動程序 235
    11.4　Linux內核配置 243
    11.5　FreeBSD內核配置 246
    11.6　可裝載內核模塊 248
    11.7　引導 250
    11.8　在雲中引導其他內核 254
    11.9　內核錯誤 255
    
    第12章　打印 258

    12.1　CUPS打印 259
    12.2　CUPS服務器管理 262
    12.3　故障排除技巧 265
     
    第二部分　連網

    第13章　TCP/IP連網 269

    13.1　TCP/IP與Internet的關系 269
    13.2　連網基礎 271
    13.3　分組尋址 275
    13.4　IP地址：殘酷的細節 277
    13.5　路由選擇 285
    13.6　IPv4 ARP與IPv6鄰居發現 287
    13.7　DCHP：動態主機配置協議 288
    13.8　安全問題 290
    13.9　基本的網絡配置 293
    13.10　Linux連網 297
    13.11　FreeBSD連網 303
    13.12　網絡故障排除 305
    13.13　網絡監控 311
    13.14　防火牆與NAT 313
    13.15　雲連網 319
    
    第14章　物理連網 326

    14.1　以太網：連網技術中的瑞士軍刀 327
    14.2　無線：流動人員的以太網 333
    14.3　SDN：軟件定義網絡 336
    14.4　網絡測試與調試 336
    14.5　樓宇布線 337
    14.6　網絡設計問題 338
    14.7　管理問題 339
    14.8　推薦廠商 340
    
    第15章　IP路由選擇 341

    15.1　詳解分組轉發 341
    15.2　路由守護進程和路由協議 344
    15.3　協議巡禮 346
    15.4　路由協議多播協調 347
    15.5　路由策略的選擇標準 348
    15.6　路由守護進程 349
    15.7　Cisco路由器 350
    
    第16章　DNS：域名系統 353

    16.1　DNS架構 353
    16.2　DNS的查詢順序 355
    16.3　DNS名稱空間 356
    16.4　DNS的工作原理 357
    16.5　DNS數據庫 363
    16.6　BIND軟件 373
    16.7　DNS分割與view語句 385
    16.8　BIND配置示例 386
    16.9　更新區文件 389
    16.10　DNS安全問題 392
    16.11　調試BIND 405
    
    第17章　單點登錄 412

    17.1　SSO的核心要素 412
    17.2　LDAP：“輕量級”目錄服務 413
    17.3　使用目錄服務登錄 418
    17.4　替代方案 423
    
    第18章　電子郵件 425

    18.1　郵件系統架構 425
    18.2　剖析郵件消息 428
    18.3　SMTP協議 430
    18.4　垃圾郵件與惡意軟件 432
    18.5　消息隱私與加密 434
    18.6　郵件別名 434
    18.7　電子郵件配置 437
    18.8　Sendmail 438
    18.9　EXIM 457
    18.10　Postfix 471
    
    第19章　Web托管 481

    19.1　HTTP：超文本傳輸協議 481
    19.2　Web軟件基礎 487
    19.3　雲環境中的Web托管 495
    19.4　Apache httpd 497
    19.5　Nginx 503
    19.6　HAProxy 507
     
    第三部分　存儲

    第20章　存儲 513

    20.1　我就是想加塊硬盤 514
    20.2　存儲硬件 516
    20.3　存儲硬件接口 522
    20.4　硬盤的安裝與低層管理 524
    20.5　逐層剖析存儲的軟件面 528
    20.6　硬盤分區 530
    20.7　邏輯捲管理 534
    20.8　RAID：廉價磁盤冗餘陣列 538
    20.9　文件系統 545
    20.10　傳統文件系統：UFS、ext4、XFS 545
    20.11　下一代文件系統：ZFS與Btrfs 551
    20.12　ZFS：解決所有的存儲問題 552
    20.13　Btrfs：Linux的“簡化版ZFS” 559
    20.14　數據備份策略 563
    
    第21章　網絡文件系統 565

    21.1　認識網絡文件服務 565
    21.2　NFS之道 567
    21.3　服務器端的NFS 572
    21.4　客戶端NFS 577
    21.5　NFSv4身份映射 579
    21.6　nfsstat：轉儲NFS統計信息 579
    21.7　專有NFS文件服務器 580
    21.8　自動掛載 581
    
    第22章　SMB 585

    22.1　Samba：UNIX的SMB服務器 585
    22.2　Samba的安裝與配置 586
    22.3　掛載SMB文件共享 590
    22.4　瀏覽SMB文件共享 590
    22.5　確保Samba的安全 590
    22.6　Samba調試 591
     
    第四部分　運維

    第23章　配置管理 597

    23.1　配置管理概述 597
    23.2　配置管理的危險 598
    23.3　配置管理要素 598
    23.4　流行的CM系統對比 602
    23.5　Ansible簡介 611
    23.6　Salt簡介 624
    23.7　比較Ansible與Salt 639
    23.8　最佳實踐 641
    
    第24章　虛擬化 644

    24.1　大話虛擬化 645
    24.2　Linux虛擬化 648
    24.3　FreeBSD bhyve 651
    24.4　VMware 651
    24.5　VirtualBox 651
    24.6　Packer 652
    24.7　Vagrant 653
    
    第25章　容器 654

    25.1　背景知識與核心概念 655
    25.2　Dcoker：開源的容器引擎 656
    25.3　容器實踐 670
    25.4　容器集群與管理 674
    
    第26章　持續集成與交付 678

    26.1　CI/CD基礎 679
    26.2　流水線 682
    26.3　Jenkin：開源的自動化服務器 686
    26.4　CI/CD實戰 688
    26.5　容器與CI/CD 698
    
    第27章　安全 701

    27.1　安全要素 702
    27.2　安全是如何被破壞的 702
    27.3　基本安全措施 704
    27.4　密碼與用戶賬戶 708
    27.5　強力安全工具 711
    27.6　密碼學入門 717
    27.7　SSH：The Secure SHell 724
    27.8　防火牆 733
    27.9　虛擬私有網絡（VPN） 734
    27.10　專業認證與標準 735
    27.11　安全信息來源 737
    27.12　如果你的站點遭受攻擊 739
    
    第28章　監控 741

    28.1　監控概覽 741
    28.2　監控文化 744
    28.3　監控平臺 744
    28.4　數據採集 748
    28.5　網絡監控 751
    28.6　系統監控 752
    28.7　應用監控 754
    28.8　安全監控 755
    28.9　SNMP：簡單網絡管理協議 757
    28.10　監控技巧 760
    
    第29章　性能分析 761

    29.1　性能調校的哲學 761
    29.2　提高性能的方法 762
    29.3　影響性能的因素 763
    29.4　竊取CPU周期 764
    29.5　分析性能問題 764
    29.6　檢查系統性能 765
    29.7　救命！我的服務器實在是太慢了 773
    
    第30章　數據中心基礎 776

    30.1　機架 777
    30.2　電力 777
    30.3　冷卻與環境 779
    30.4　數據中心可靠性分級 782
    30.5　數據中心安全 783
    30.6　工具 784
    
    第31章　方法論、策略與政治 786

    31.1　大一統理論：DevOps 787
    31.2　工單與任務管理系統 790
    31.3　本地文檔維護 792
    31.4　環境分離 794
    31.5　災難管理 795
    31.6　IT策略與規程 797
    31.7　服務水平協議 799
    31.8　合規：規章與標準 801
    31.9　法律問題 803
    31.10　組織、會議及其他資源 805

    附錄　系統管理簡史 807



