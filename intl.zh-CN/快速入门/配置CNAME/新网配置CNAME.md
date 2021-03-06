# 新网配置CNAME {#task_187634 .task}

本文为您介绍了如何在新网配置CNAME。如果您想启用CDN加速服务，您需要将加速域名指向CDN节点的CNAME地址，这样访问加速域名的请求才能转发到CDN节点上，达到加速效果。

1.  获取加速域名的CNAME地址。 
    1.  登录[CDN控制台](https://cdnnext.console.aliyun.com/overview)。
    2.  进入域名管理页面，复制加速域名对应的CNAME值。 

        ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/5113/155917899845282_zh-CN.png)

2.  添加CNAME记录。 前往新网的域名解析控制台, 进入对应域名的域名解析页，选择**添加新的别名**。

    -   记录类型：选择`CNAME`。
    -   主机记录：加速域名的前缀。

        |如果您的加速域名为...|主机记录为...|
        |:-----------|:-------|
        |`testcdn.aliyun.com`|`testcdn`|
        |`www.aliyun.com`|`www`|
        |`aliyun.com`|`@`|
        |`*.aliyun.com`|`*`|

    -   记录值：您进行步骤1时复制的CNAME值。
    -   解析线路：默认值。
    -   TTL：默认值。
    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/5115/155917899845324_zh-CN.png)

    填写完单击**提交**，配置CNAME完毕。CNAME配置生效后，CDN服务也会立即生效。

    **说明：** 

    -   CNAME配置生效时间：新增CNAME记录会实时生效，而修改CNAME记录需要最多72小时生效时间。
    -   配置完CNAME后，由于状态更新约有10分钟延迟，阿里云CDN控制台的域名列表可能仍提示“未配置CNAME”，请您忽略即可。
3.  验证CNAME配置是否生效。 

    配置CNAME后，不同的DNS服务商CNAME生效的时间也不同。您可以通过输入`ping`或`dig`您所添加的加速域名来验证，如果被转向`*.*kunlun*.com`，即表示CNAME配置已经生效，CDN功能也已生效。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/5114/155917899845299_zh-CN.png)


