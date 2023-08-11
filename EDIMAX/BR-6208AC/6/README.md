# EDIMAX

## Affected version:

```

```

To download the firmware: 

## Description

EDIMAX BR-6208AC_1.32中/goform/formWlSiteSurvey API中进行了不正确的越界写操作。

通过控制done， ifname参数可以导致程序进入不正确的越界写的代码片段执行越界写入。

攻击者可以通过向基于web的管理界面发送精心制作的请求来利用此漏洞。一个成功的漏洞利用可以允许攻击者攻击设备的/bin/webs服务，从而造成严重的拒绝服务攻击。

## Poc&&Exp

The content of this part is placed in the additional information
