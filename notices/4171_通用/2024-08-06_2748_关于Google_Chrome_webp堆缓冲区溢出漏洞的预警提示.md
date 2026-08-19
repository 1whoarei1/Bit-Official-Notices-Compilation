关于Google Chrome webp堆缓冲区溢出漏洞的预警提示

来源：主站最新通知
发布日期：2024-08-06
原文链接：https://www.bit.edu.cn/tzgg17/wlfw/c34cb01af53b416192de10247c45441f.htm

关于Google Chrome webp堆缓冲区溢出漏洞的预警提示

发布日期：2024-08-06

漏洞概述：

2023年9月11日，谷歌针对其开发的图像格式WebP中一个严重的堆缓冲区溢出漏洞发布了紧急补丁。这个零日漏洞编号为CVE-2023-4863（CNNVD编号:CNNVD-202309-784），允许远程攻击者通过恶意WebP图像执行越界内存写入。

这个漏洞不仅仅影响谷歌的Chrome浏览器，同时还因影响所有支持WebP格式的浏览器，因此微软、苹果和Mozilla等公司也陆续发布了浏览器版本更新。更多细节显示，虽然谷歌最初称其为是WebP的缺陷，但安全研究人员指出，这个问题其实存在于开源Libwebp库中。

影响范围：

● Google-Chrome

● Mozilla-Firefox

● Microsoft-Edge Chromium

● Mozilla-Firefox Esr

● Webmproject-Libwebp

● Microsoft-Edge

● Mozilla-Mozilla Thunderbird

● Debian-Debian Linux

● Fedora Project-Fedora

● NetApp-NetApp Active IQ Unified Manager

修复建议：

1、官方升级

目前官方已发布安全版本修复此漏洞，建议受影响的用户及时升级防护：
https://www.google.com/chrome/

2、手动升级

在Chrome菜单栏—“帮助”—“关于Google Chrome”检查更新，更新后重新启动即可。
