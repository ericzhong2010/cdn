# CDN API概述 {#reference_ckk_xml_vdb .reference}

本文档介绍了阿里云CDN的各API名称。您可以分别点击链接查看各API接口的具体参数。

## 服务操作接口 {#section_tsp_qnl_vdb .section}

|API|描述|
|:--|:-|
|[OpenCdnService](intl.zh-CN/API 参考/服务操作接口/OpenCdnService.md)|开通CDN服务|
|[DescribeCdnService](intl.zh-CN/API 参考/服务操作接口/DescribeCdnService.md)|查询CDN服务状态。包括当前计费类型，服务开通时间，下次生效的计费类型，当前业务状态等|
|[ModifyCdnService](intl.zh-CN/API 参考/服务操作接口/ModifyCdnService.md)|变更CDN服务的计费类型|

## 刷新预热接口 {#section_tzc_vnl_vdb .section}

|API|描述|
|:--|:-|
|[RefreshObjectCaches](intl.zh-CN/API 参考/刷新预热接口/RefreshObjectCaches.md)|刷新节点上的文件内容，支持批量|
|[PushObjectCache](intl.zh-CN/API 参考/刷新预热接口/PushObjectCache.md)|将源站的内容主动预热到L2 Cache节点上，用户首次访问可直接命中缓存，缓解源站压力，支持批量|
|[DescribeRefreshTasks](intl.zh-CN/API 参考/刷新预热接口/DescribeRefreshTasks.md)|查询预热刷新状态，是否在全网生效|
|[DescribeRefreshQuota](intl.zh-CN/API 参考/刷新预热接口/DescribeRefreshQuota.md)|查询预热刷新操作余量|

## 日志信息接口 {#section_c3h_xnl_vdb .section}

|API|描述|
|:--|:-|
|[DescribeCdnDomainLogs](intl.zh-CN/API 参考/日志信息接口/DescribeCdnDomainLogs.md)|获取指定域名的原始访问日志的下载地址|
|[DescribeCustomLogConfig](intl.zh-CN/API 参考/日志信息接口/DescribeCustomLogConfig.md)|根据configId查询自定义日志配置详细信息|
|[DescribeDomainCustomLogConfig](intl.zh-CN/API 参考/日志信息接口/DescribeDomainCustomLogConfig.md)|获取域名自定义日志格式配置信息|
|[DescribeUserCustomLogConfig](intl.zh-CN/API 参考/日志信息接口/DescribeUserCustomLogConfig.md)|获取用户所有自定义日志配置信息|
|[ListDomainsByLogConfigId](intl.zh-CN/API 参考/日志信息接口/ListDomainsByLogConfigId.md)|查询应用某自定义日志格式的所有域名列表|
|[ModifyDomainCustomLogConfig](intl.zh-CN/API 参考/日志信息接口/ModifyDomainCustomLogConfig.md)|修改域名所属日志自定义日志配置信息|
|[ModifyUserCustomLogConfig](intl.zh-CN/API 参考/日志信息接口/ModifyUserCustomLogConfig.md)|修改用户下自定义日志配置信息|

## 配置操作接口 {#section_lqd_5nl_vdb .section}

|API|描述|
|:--|:-|
|[DescribeDomainConfigs](intl.zh-CN/API 参考/配置操作接口/DescribeDomainConfigs.md)|查询域名配置|
|[SetOptimizeConfig](intl.zh-CN/API 参考/配置操作接口/SetOptimizeConfig.md)|设置页面优化|
|[SetPageCompressConfig](intl.zh-CN/API 参考/配置操作接口/SetPageCompressConfig.md)|设置智能压缩|
|[SetIgnoreQueryStringConfig](intl.zh-CN/API 参考/配置操作接口/SetIgnoreQueryStringConfig.md)|设置过滤参数|
|[SetRangeConfig](intl.zh-CN/API 参考/配置操作接口/SetRangeConfig.md)|设置Range回源|
|[SetVideoSeekConfig](intl.zh-CN/API 参考/配置操作接口/SetVideoSeekConfig.md)|设置拖拽播放|
|[SetSourceHostConfig](intl.zh-CN/API 参考/配置操作接口/SetSourceHostConfig.md)|设置回源host|
|[SetErrorPageConfig](intl.zh-CN/API 参考/配置操作接口/SetErrorPageConfig.md)|设置404页面|
|[SetForceRedirectConfig](intl.zh-CN/API 参考/配置操作接口/SetForceRedirectConfig.md)|设置强制跳转|
|[SetRefererConfig](intl.zh-CN/API 参考/配置操作接口/SetRefererConfig.md)|设置防盗链|
|[SetFileCacheExpiredConfig](intl.zh-CN/API 参考/配置操作接口/SetFileCacheExpiredConfig.md)|设置文件类型缓存策略|
|[SetPathCacheExpiredConfig](intl.zh-CN/API 参考/配置操作接口/SetPathCacheExpiredConfig.md)|设置路径缓存策略|
|[ModifyFileCacheExpiredConfig](intl.zh-CN/API 参考/配置操作接口/ModifyFileCacheExpiredConfig.md)|修改文件类型缓存策略|
|[ModifyPathCacheExpiredConfig](intl.zh-CN/API 参考/配置操作接口/ModifyPathCacheExpiredConfig.md)|修改路径缓存策略|
|[DeleteCacheExpiredConfig](intl.zh-CN/API 参考/配置操作接口/DeleteCacheExpiredConfig.md)|删除缓存配置|
|[SetReqAuthConfig](intl.zh-CN/API 参考/配置操作接口/SetReqAuthConfig.md)|设置鉴权|
|[SetHttpHeaderConfig](intl.zh-CN/API 参考/配置操作接口/SetHttpHeaderConfig.md)|设置HTTP头信息|
|[ModifyHttpHeaderConfig](intl.zh-CN/API 参考/配置操作接口/ModifyHttpHeaderConfig.md)|修改HTTP头信息|
|[DeleteHttpHeaderConfig](intl.zh-CN/API 参考/配置操作接口/DeleteHttpHeaderConfig.md)|删除HTTP头信息|
|[SetDomainServerCertificate](intl.zh-CN/API 参考/配置操作接口/SetDomainServerCertificate.md)|配置证书|
|[SetIpBlackListConfig](intl.zh-CN/API 参考/配置操作接口/SetIpBlackListConfig.md)|设置加速域名的IP黑名单|

## 域名操作接口 {#section_iv2_tnl_vdb .section}

|API|描述|
|:--|:-|
|[AddCdnDomain](intl.zh-CN/API 参考/域名操作接口/AddCdnDomain.md)|添加加速域名，一次只能提交一个加速域名|
|[DescribeUserDomains](intl.zh-CN/API 参考/域名操作接口/DescribeUserDomains.md)|查询用户名下所有的域名与状态|
|[DescribeCdnDomainDetail](intl.zh-CN/API 参考/域名操作接口/DescribeCdnDomainDetail.md)|获取指定加速域名配置的基本信息|
|[ModifyCdnDomain](intl.zh-CN/API 参考/域名操作接口/ModifyCdnDomain.md)|修改加速域名，目前支持修改源站|
|[StartCdnDomain](intl.zh-CN/API 参考/域名操作接口/StartCdnDomain.md)|启用状态为“停用”的加速域名，将DomainStatus变更为online|
|[StopCdnDomain](intl.zh-CN/API 参考/域名操作接口/StopCdnDomain.md)|停用某个加速域名，将DomainStatus变更为offline|
|[DeleteCdnDomain](intl.zh-CN/API 参考/域名操作接口/DeleteCdnDomain.md)|【慎用】删除当前加速域名，每次只能提交一个加速域名|
|[DescribeDomainsBySource](intl.zh-CN/API 参考/域名操作接口/DescribeDomainsBySource.md)|根据源站查询对应的域名信息|

## 辅助工具接口 {#section_ttd_ynl_vdb .section}

|API|描述|
|:--|:-|
|[DescribeIpInfo](intl.zh-CN/API 参考/辅助工具接口/DescribeIpInfo.md)|验证指定的IP是否为阿里云CDN节点的IP地址|

## 资源监控接口 {#section_mn2_wnl_vdb .section}

|API|Description|
|:--|:----------|
|[DescribeDomainFlowData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainFlowData.md)|获取加速域名的网络流量监控数据，单位：byte|
|[DescribeDomainSrcBpsData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainSrcBpsData.md)|获取加速域名的回源带宽监控数据，单位：bit/second|
|[DescribeDomainSrcFlowData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainSrcFlowData.md)|获取加速域名的回源流量监控数据，单位：bit|
|[DescribeDomainHitRateData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainHitRateData.md)|获取加速域名的字节命中率（命中字节百分比）|
|[DescribeDomainReqHitRateData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainReqHitRateData.md)|获取加速域名的请求命中率（命中请求百分比）|
|[DescribeDomainQpsData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainQpsData.md)|获取加速域名的每秒访问次数QPS|
|[DescribeDomainHttpCodeData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainHttpCodeData.md)|获取加速域名最小5分钟粒度的HTTP返回码占比数据|
|[DescribeDomainsUsageByDay](intl.zh-CN/API 参考/资源监控接口/DescribeDomainsUsageByDay.md)|获取加速域名天粒度监控统计数据|
|[DescribeTopDomainsByFlow](intl.zh-CN/API 参考/资源监控接口/DescribeTopDomainsByFlow.md)|获取用户按流量排名的域名|
|[DescribeDomainPvData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainPvData.md)|获取加速域名最小1小时粒度的PV页面访问统计|
|[DescribeDomainUvData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainUvData.md)|获取加速域名最小1小时粒度的UV页面独立访问统计|
|[DescribeDomainRegionData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainRegionData.md)|获取加速域名天粒度的用户区域分布数据统计|
|[DescribeDomainISPData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainISPData.md)|获取加速域名天粒度的用户运营商分布数据统计|
|[DescribeDomainTopUrlVisit](intl.zh-CN/API 参考/资源监控接口/DescribeDomainTopUrlVisit.md)|获取加速域名某天内的热门URL列表|
|[DescribeDomainTopReferVisit](intl.zh-CN/API 参考/资源监控接口/DescribeDomainTopReferVisit.md)|获取加速域名某天的热门页面引用次数排名|
|[DescribeDomainFileSizeProportionData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainFileSizeProportionData.md)|获取加速域名最小1小时粒度的文件大小占比统计|
|[DescribeCdnRegionAndIsp](intl.zh-CN/API 参考/资源监控接口/DescribeCdnRegionAndIsp.md)|获取区域和运营商列表|
|[DescribeDomainBpsDataByTimeStamp](intl.zh-CN/API 参考/资源监控接口/DescribeDomainBpsDataByTimeStamp.md)|获取加速域名的在某个时刻不同Locate和Isp上的带宽数据，单位 bit/second|
|[DescribeDomainMax95BpsData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainMax95BpsData.md)|获取加速域名95带宽峰值监控数据，单位：bit/second|
|[DescribeDomainPathData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainPathData.md)|获取加速域名路径级别的5分钟维度的监控数据，包括流量和访问次数|
|[DescribeL2VipsByDomain](intl.zh-CN/API 参考/资源监控接口/DescribeL2VipsByDomain.md)|按域名查询L2节点vip列表。配置白名单后才可以生效|
|[DescribeDomainRealTimeBpsData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainRealTimeBpsData.md)|获取域名1分钟粒度带宽数据|
|[DescribeDomainRealTimeByteHitRateData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainRealTimeByteHitRateData.md)|获取域名1分钟粒度字节命中率数据|
|[DescribeDomainRealTimeQpsData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainRealTimeQpsData.md)|获取域名1分钟粒度每秒访问次数数据|
|[DescribeDomainRealTimeReqHitRateData](intl.zh-CN/API 参考/资源监控接口/DescribeDomainRealTimeReqHitRateData.md)|获取域名1分钟粒度请求命中率数据|

## 全站加速接口 {#section_szw_dlx_yfb .section}

|API|描述|
|:--|:-|
|[SetDynamicConfig](intl.zh-CN/API 参考/全站加速接口/SetDynamicConfig.md)|全站加速，缓存规则的配置|

