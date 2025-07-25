---
title: fancyss
description: fancyss 是一款基于梅林固件的科学上网插件，支持多种协议和平台，提供丰富的功能和灵活的配置选项
---

# fancyss

## 插件特色

- 多平台支持：博通armv7，博通armv8，联发科Filogic 830 MT7986A，高通ipq系列
- 多客户端支持：Shadowsocks、ShadowsocksR、V2ray、Xray、Trojan、NaïveProxy、TuicV5、Hysteria2
- shadowsocks支持SIP003插件：simple-obfs；V2ray和Xray支持多种协议配置
- 多种模式支持：gfwlist模式、大陆白名单、游戏模式、全局模式、回国模式
- 提供多种现成的DNS方案，并且可以自由方便的进行DNS方案自定义配置
- 支持SS/SSR/V2ray/Xray/Trojan节点的在线订阅，支持节点生成二维码用以分享
- 故障转移、主备切换、负载均衡、定时重启、定时订阅、规则更新、二进制更新
- 支持kcptun、udpspeeder、udp2raw，可以实现代理加速，游戏加速，应对丢包等
- 同时提供full版本和lite版本，hnd_lite版本安装后占用不到8MB的空间，适合小jffs机型
- armv8机型支持tcp fast open和ss/ssr/trojan多核心运行

## 支持机型/固件 <Pill name="最新固件下载地址" link="https://fw.koolcenter.com/" image="https://fw.koolcenter.com/theme/favicon.svg"  alt='koolcenter icon'/>

> 以下为 fancyss 3.0 支持的机型/固件，点击机型可以前往相应固件下载地址

| 机型/固件下载                                                                       | 类型 | 平台            | CPU       | 架构  | linux 内核 | fancyss 版本   |
| ----------------------------------------------------------------------------------- | ---- | --------------- | --------- | ----- | ---------- | -------------- |
| [R6300V2](https://fw.koolcenter.com/KoolCenter_Merlin_New_Gen_386/Netgear/R6300v2/) | 梅改 | 6.x.4708        | BCM4708   | armv7 | 2.6.36.4   | fancyss_arm    |
| [RT-AC68U](https://www.koolcenter.com/posts/38)                                     | 梅改 | 6.x.4708        | BCM4708   | armv7 | 2.6.36.4   | fancyss_arm    |
| [RT-AC88U](https://www.koolcenter.com/posts/39)                                     | 梅改 | 7.14.114.x      | BCM4709   | armv7 | 2.6.36.4   | fancyss_arm    |
| [RT-AC3100](https://www.koolcenter.com/posts/40)                                    | 梅改 | 7.14.114.x      | BCM4709   | armv7 | 2.6.36.4   | fancyss_arm    |
| [RT-AC5300](https://www.koolcenter.com/posts/41)                                    | 梅改 | 7.14.114.x      | BCM4709   | armv7 | 2.6.36.4   | fancyss_arm    |
| [RT-AC86U](https://www.koolcenter.com/posts/36)                                     | 梅改 | hnd             | BCM4906   | armv8 | 4.1.27     | fancyss_hnd_v8 |
| [RT-AC86U](https://www.koolcenter.com/posts/139)                                    | 官改 | hnd             | BCM4906   | armv8 | 4.1.27     | fancyss_hnd_v8 |
| [GT-AC2900](https://fw.koolcenter.com/KoolCenter_Merlin_New_Gen_386/GT-AC2900/)     | 梅改 | hnd             | BCM4906   | armv8 | 4.1.27     | fancyss_hnd_v8 |
| [GT-AC2900](https://www.koolcenter.com/posts/37)                                    | 官改 | hnd             | BCM4906   | armv8 | 4.1.27     | fancyss_hnd_v8 |
| [GT-AC5300](https://www.koolcenter.com/posts/12)                                    | 官改 | hnd             | BCM4908   | armv8 | 4.1.27     | fancyss_hnd_v8 |
| [RT-AX88U](https://www.koolcenter.com/posts/34)                                     | 梅改 | axhnd           | BCM4908   | armv8 | 4.1.51     | fancyss_hnd_v8 |
| [RT-AX88U](https://www.koolcenter.com/posts/142)                                    | 官改 | axhnd           | BCM4908   | armv8 | 4.1.51     | fancyss_hnd_v8 |
| [RAX80](https://www.koolcenter.com/posts/43)                                        | 梅改 | axhnd           | BCM4908   | armv8 | 4.1.51     | fancyss_hnd_v8 |
| [GT-AX11000](https://www.koolcenter.com/posts/140)                                  | 官改 | axhnd           | BCM4908   | armv8 | 4.1.51     | fancyss_hnd_v8 |
| [GT-AX11000](https://www.koolcenter.com/posts/35)                                   | 梅改 | axhnd           | BCM4908   | armv8 | 4.1.51     | fancyss_hnd_v8 |
| [RT-AX92U](https://www.koolcenter.com/posts/20)                                     | 官改 | axhnd           | BCM4906   | armv8 | 4.1.51     | fancyss_hnd_v8 |
| [TUF-AX3000](https://www.koolcenter.com/posts/11)                                   | 官改 | axhnd.675x      | BCM6750   | armv7 | 4.1.52     | fancyss_hnd    |
| [TUF-AX5400](https://www.koolcenter.com/posts/130)                                  | 梅改 | axhnd.675x      | BCM6750   | armv7 | 4.1.52     | fancyss_hnd    |
| [TUF-AX5400](https://www.koolcenter.com/posts/141)                                  | 官改 | axhnd.675x      | BCM6750   | armv7 | 4.1.52     | fancyss_hnd    |
| [RT-AX58U](https://www.koolcenter.com/posts/130)                                    | 梅改 | axhnd.675x      | BCM6750   | armv7 | 4.1.52     | fancyss_hnd    |
| [RAX50](https://www.koolcenter.com/posts/130)                                       | 梅改 | axhnd.675x      | BCM6750   | armv7 | 4.1.52     | fancyss_hnd    |
| [RT-AX82U](https://www.koolcenter.com/posts/18)                                     | 官改 | axhnd.675x      | BCM6750   | armv7 | 4.1.52     | fancyss_hnd    |
| [RT-AX82U](https://www.koolcenter.com/posts/130)                                    | 梅改 | axhnd.675x      | BCM6750   | armv7 | 4.1.52     | fancyss_hnd    |
| [ZenWiFi_XT8](https://www.koolcenter.com/posts/137)                                 | 官改 | axhnd.675x      | BCM6755   | armv7 | 4.1.52     | fancyss_hnd    |
| [ZenWiFi_XT8](https://www.koolcenter.com/posts/130)                                 | 梅改 | axhnd.675x      | BCM6755   | armv7 | 4.1.52     | fancyss_hnd    |
| [ZenWiFi_XD4](https://www.koolcenter.com/posts/21)                                  | 官改 | axhnd.675x      | BCM6755   | armv7 | 4.1.52     | fancyss_hnd    |
| [RT-AX56U_V2](https://www.koolcenter.com/posts/16)                                  | 官改 | axhnd.675x      | BCM6755   | armv7 | 4.1.52     | fancyss_hnd    |
| [RT-AX1800](https://www.koolcenter.com/posts/16)                                    | 梅改 | axhnd.675x      | BCM6755   | armv7 | 4.1.52     | fancyss_hnd    |
| [RT-AX56U](https://www.koolcenter.com/posts/130)                                    | 梅改 | axhnd.675x      | BCM6755   | armv7 | 4.1.52     | fancyss_hnd    |
| [RAX70](https://www.koolcenter.com/posts/130)                                       | 梅改 | axhnd.675x      | BCM6755   | armv7 | 4.1.52     | fancyss_hnd    |
| [RT-AX68U](https://www.koolcenter.com/posts/136)                                    | 官改 | 5.02L.07p2axhnd | BCM4906   | armv8 | 4.1.52     | fancyss_hnd_v8 |
| [RT-AX68U](https://www.koolcenter.com/posts/33)                                     | 梅改 | 5.02L.07p2axhnd | BCM4906   | armv8 | 4.1.52     | fancyss_hnd_v8 |
| [RT-AX86U](https://www.koolcenter.com/posts/135)                                    | 官改 | 5.02L.07p2axhnd | BCM4908   | armv8 | 4.1.52     | fancyss_hnd_v8 |
| [RT-AX86U](https://www.koolcenter.com/posts/5)                                      | 梅改 | 5.02L.07p2axhnd | BCM4908   | armv8 | 4.1.52     | fancyss_hnd_v8 |
| [GT-AXE11000](https://www.koolcenter.com/posts/130)                                 | 梅改 | 5.02L.07p2axhnd | BCM4908   | armv8 | 4.1.52     | fancyss_hnd_v8 |
| [GT-AX6000](https://www.koolcenter.com/posts/125)                                   | 官改 | 5.04axhnd.675x  | BCM4912   | armv8 | 4.19.183   | fancyss_hnd_v8 |
| [GT-AX6000](https://www.koolcenter.com/posts/148)                                   | 梅改 | 5.04axhnd.675x  | BCM4912   | armv8 | 4.19.183   | fancyss_hnd_v8 |
| [ZenWiFi_Pro_XT12](https://www.koolcenter.com/posts/133)                            | 官改 | 5.04axhnd.675x  | BCM4912   | armv8 | 4.19.183   | fancyss_hnd_v8 |
| [ZenWiFi_Pro_XT12](https://www.koolcenter.com/posts/149)                            | 梅改 | 5.04axhnd.675x  | BCM4912   | armv8 | 4.19.183   | fancyss_hnd_v8 |
| [TUF-AX3000_V2](https://www.koolcenter.com/posts/161)                               | 官改 | 5.04axhnd.675x  | BCM6756   | armv7 | 4.19.183   | fancyss_hnd    |
| [RT-AX86U PRO](https://www.koolcenter.com/posts/228)                                | 官改 | 5.04axhnd.675x  | BCM4912   | armv8 | 4.19.183   | fancyss_hnd_v8 |
| RT-AX86U PRO                                                                        | 梅改 | 5.04axhnd.675x  | BCM4912   | armv8 | 4.19.183   | fancyss_hnd_v8 |
| GT-AX11000 PRO                                                                      | 官改 | 5.04axhnd.675x  | BCM4912   | armv8 | 4.19.183   | fancyss_hnd_v8 |
| GT-AX11000 PRO                                                                      | 梅改 | 5.04axhnd.675x  | BCM4912   | armv8 | 4.19.183   | fancyss_hnd_v8 |
| RT-BE86U                                                                            | 官改 | 5.04behnd.4916  | BCM4916   | armv8 | 4.19.275   | fancyss_hnd_v8 |
| RT-BE88U                                                                            | 官改 | 5.04behnd.4916  | BCM4916   | armv8 | 4.19.275   | fancyss_hnd_v8 |
| GT-BE96                                                                             | 官改 | 5.04behnd.4916  | BCM4916   | armv8 | 4.19.275   | fancyss_hnd_v8 |
| RT-BE96U                                                                            | 梅改 | 5.04behnd.4916  | BCM4916   | armv8 | 4.19.275   | fancyss_hnd_v8 |
| GT-BE98_PRO                                                                         | 梅改 | 5.04behnd.4916  | BCM4916   | armv8 | 4.19.275   | fancyss_hnd_v8 |
| [RT-AX89X](https://www.koolcenter.com/posts/126)                                    | 官改 | qca-ipq806x     | ipq8074/a | armv7 | 4.4.60     | fancyss_qca    |
| ZenWiFi_BD4                                                                         | 官改 | qca-ipq53xx     | IPQ5322   | armv7 | 5.4.213    | fancyss_ipq32  |
| TUF-BE6500                                                                          | 官改 | qca-ipq53xx     | IPQ5322   | armv8 | 5.4.213    | fancyss_ipq64  |
| TX-AX6000                                                                           | 官改 | mtk-MT798X      | MT7986A   | armv8 | 5.4.182    | fancyss_mtk    |
| TUF-AX4200Q                                                                         | 官改 | mtk-MT798X      | MT7986A   | armv8 | 5.4.182    | fancyss_mtk    |
| GS7                                                                                 | 官改 | mtk-7988_7990   | MT7988D   | armv8 | 5.4.281    | fancyss_mtk    |
| ZenWiFi_BT8P                                                                        | 官改 | mtk-7988_7990   | MT7988D   | armv8 | 5.4.281    | fancyss_mtk    |

## 版本选择

fancyss 3.0支持hnd、hnd_v8、qca、arm、mtk 、ipq32、ipq64七个平台，每个平台又有full版本和lite版本

full版本为全功能版本，支持SS、 SSR、V2ray、 Xray、Trojan、NaïveProxy、TuicV5、Hysteria2 八种客户端，安装包体积较大

1. full版本虽然支持tuic，但因作者已放弃项目，所以默认不自带tuic二进制
2. full版本虽然支持kcptun，但不提供kcptun二进制，如果使用kcptun加速，会提示下载二进制
3. full版本默认不提供udp2raw和udpspeeder二进制，如需要使用，会提示下载二进制

lite版本为精简版本，支持SS、 SSR、 V2ray、 Xray、 Trojan 五种客户端，安装包小巧，以下为lite版本精简内容：

1. lite版本移除了NaïveProxy支持及其相关二进制文件：naive、ipt2socks
2. lite版本移除了UDP加速功能及其二进制文件：speederv1、speederv2、udp2raw
3. lite版本移除了KCP加速功能及其二进制文件：kcptun
4. lite版本移除了直连解析的DNS方案及其二进制：chinadns1、chinadns2、https_dns_proxy
5. lite版本移除了haveged，因为现在较新的固件系统自带了熵增软件
6. lite版本移除了shadowsocks-rust替换shadowsocks-libev功能，默认由shadowsocks-libev运行ss协议
7. lite版本移除了socks5页面及其脚本及其acl规则文件

如果是不折腾以上被精简功能的用户，完全可以使用体积更小的lite版本

RT-AX56U_V2、RT-AX57 这种jffs分区极小(15MB)的机型，直接使用lite版本即可

要切换为lite版本，直接安装lite版本的离线安装包即可，以后在线更新也会维持为lite版本

要切换为full版本，直接安装full版本的离线安装包即可，以后在线更新也会维持为full版本

RT-AX86U、GT-AX6000等armv8机型（见上表），从3.0.6开始建议安装fancyss_hnd_v8版本，当然fancyss_hnd同样兼容

## 插件下载

插件下载有两种方式：

1. 在 `packages` 目录下，点击 tar.gz 后缀文件，下载当前最新版本的离线安装包
2. 在 <Pill name="fancyss_history_package" link="https://github.com/hq450/fancyss_history_package" :icon="{ icon: 'cib:github', color: { light: '#181717', dark: '#ffffff' }, alt: 'GitHub 图标' }" /> 项目中，包含**历史版本**和**最新版本**的离线安装包

插件离线包下载导航：

| 平台   | 最新full版本下载                                                                                               | 最新lite版本下载                                                                                               | 历史版本下载（包含最新版）                                                                    |
| ------ | -------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| hnd    | [fancyss_hnd_full](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_hnd_full.tar.gz)       | [fancyss_hnd_lite](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_hnd_lite.tar.gz)       | [fancyss_hnd](https://github.com/hq450/fancyss_history_package/tree/master/fancyss_hnd)       |
| hnd_v8 | [fancyss_hnd_v8_full](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_hnd_v8_full.tar.gz) | [fancyss_hnd_v8_lite](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_hnd_v8_lite.tar.gz) | [fancyss_hnd_v8](https://github.com/hq450/fancyss_history_package/tree/master/fancyss_hnd_v8) |
| qca    | [fancyss_qca_full](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_qca_full.tar.gz)       | [fancyss_qca_lite](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_qca_lite.tar.gz)       | [fancyss_qca](https://github.com/hq450/fancyss_history_package/tree/master/fancyss_qca)       |
| arm    | [fancyss_arm_full](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_arm_full.tar.gz)       | [fancyss_arm_lite](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_arm_lite.tar.gz)       | [fancyss_arm](https://github.com/hq450/fancyss_history_package/tree/master/fancyss_arm)       |
| mtk    | [fancyss_mtk_full](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_mtk_full.tar.gz)       | [fancyss_mtk_lite](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_mtk_lite.tar.gz)       | [fancyss_mtk](https://github.com/hq450/fancyss_history_package/tree/master/fancyss_mtk)       |
| ipq32  | [fancyss_ipq32_full](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_ipq32_full.tar.gz)   | [fancyss_ipq32_lite](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_ipq32_lite.tar.gz)   | [fancyss_ipq32](https://github.com/hq450/fancyss_history_package/tree/master/fancyss_ipq32)   |
| ipq64  | [fancyss_ipq64_full](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_ipq64_full.tar.gz)   | [fancyss_ipq64_lite](https://raw.githubusercontent.com/hq450/fancyss/3.0/packages/fancyss_ipq64_lite.tar.gz)   | [fancyss_ipq64](https://github.com/hq450/fancyss_history_package/tree/master/fancyss_ipq64)   |

## 插件安装

1. 离线安装：下载并校验好离线安装包后，在软件中心内使用**离线安装**/**手动安装**功能，选择安装包后上传并安装即可。

2. 命令安装：(以 fancyss_hnd_lite.tar.gz 为例，先下载好安装包，并将其上传到路由器的/tmp 目录)

   ```bash
   mv /tmp/fancyss_hnd_lite.tar.gz /tmp/shadowsocks.tar.gz
   tar -zxvf /tmp/shadowsocks.tar.gz
   sh /tmp/shadowsocks/install.sh
   ```

## 关于皮肤

目前插件皮肤支持以下版本：

asuswrt：经典 asuswrt 皮肤

rog：华硕红色 rog 皮肤

tuf：华硕橙色 tuf 皮肤

tx：华硕天选青色皮肤

## 注意事项

- 强烈建议使用 chrome 或者 chrouium 内核的浏览器！以保证最佳兼容性！
- 强烈建议在 `最新版本的固件` 和 `最新版本软件中心` 上使用 fancyss_hnd！
- 插件会自动跟随当前固件的皮肤类型，支持 assuwrt、rog、tuf 三种皮肤。
- 一些机型的联名版，只要刷了官改/梅林改版固件的，均能安装本插件！

## 目录说明

1. **fancyss**：插件代码主目录，由 build.sh 打包成不同路由器的离线安装包
2. **binaries**：一些在线更新的二进制程序，如 v2ray、xray
3. **packages**：不同平台的离线安装包的最新版本，用于插件的在线更新
4. **rules**：插件的规则文件，如 gfwlist.conf、chnroute.txt、cdn.txt

## 相关链接

<Pill
  name="fancyss 更新日志"
  link="https://github.com/hq450/fancyss/blob/3.0/Changelog.txt"
  :icon="{ icon: 'cib:github', color: { light: '#181717', dark: '#ffffff' }, alt: 'GitHub 图标' }"
/>
<br />
<Pill
  name="官改/梅改固件下载【官方网站】（最新固件）"
  link="https://www.koolcenter.com/"
  image="https://fw.koolcenter.com/theme/favicon.svg"
  alt="koolcenter icon"
/>
<br />
<Pill
  name="官改/梅改固件下载【固件镜像】（次新固件）"
  link="https://fw.koolcenter.com/"
  image="https://fw.koolcenter.com/theme/favicon.svg"
  alt="koolcenter icon"
/>

## 配置使用

### 第 1 步 - 打开梅林固件「软件中心」的「科学上网」插件

![fancyss](https://i.theojs.cn/docs/image_1k10u2w.webp '打开“软件中心”——“科学上网”')

### 第 2 步 - 清空配置

:::tip
首次配置，请看第 3 步。如之前有进行过配置，强烈建议「清空配置」后再参照教程继续设置，以确保配置正确性。
:::
![fancyss](https://i.theojs.cn/docs/image_18vardl.webp '清空配置')

### 第 3 步 - 订阅节点

:::tip
弹框选择「订阅节点」。如没弹框，直接看第 4 步，手动选择「更新管理」选项卡。
:::
![fancyss](https://i.theojs.cn/docs/image_upeb6r.webp '订阅节点')

### 第 4 步 - 订阅节点配置「更新管理」

![fancyss](https://i.theojs.cn/docs/image_2vj9pj.webp '更新管理')

### 第 5 步 - 配置「DNS 设定」

![fancyss](https://i.theojs.cn/docs/image_18d55uv.webp 'DNS设定')

### 第 6 步 - 启动设置

![fancyss](https://i.theojs.cn/docs/image_1fhyjy6.webp '启动设置')

## 其他事项

### 更新订阅

- 「删除全部订阅节点」
- 「保存并订阅」

:::tip
因为节点可能会定期调整，为了确保订阅的节点信息与官网所提供的节点信息一致，请定期（1~2 周）更新订阅。由于梅林的科学上网插件不会覆盖节点，直接更新订阅会导致节点排序混乱。推荐按照上述步骤操作。
:::
![fancyss](https://i.theojs.cn/docs/image_1d6qvr3.webp '更新订阅')

## 异常解决方案

### DNS服务工作异常，无法解析域名

- **DNS方案设置** - 进阶
- **DNS主方案** - smartdns
- **节点域名解析** - google 8.8.8.8
