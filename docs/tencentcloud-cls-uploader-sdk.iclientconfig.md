<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [tencentcloud-cls-uploader-sdk](./tencentcloud-cls-uploader-sdk.md) &gt; [IClientConfig](./tencentcloud-cls-uploader-sdk.iclientconfig.md)

## IClientConfig interface

ClientConfig 参数配置

**Signature:**

```typescript
export interface IClientConfig 
```

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [credential?](./tencentcloud-cls-uploader-sdk.iclientconfig.credential.md) |  | [QCloudCredential](./tencentcloud-cls-uploader-sdk.qcloudcredential.md) | _(Optional)_ 永久密钥 |
|  [getAgent?](./tencentcloud-cls-uploader-sdk.iclientconfig.getagent.md) |  | () =&gt; any | _(Optional)_ 获取代理函数 |
|  [getAuthorization?](./tencentcloud-cls-uploader-sdk.iclientconfig.getauthorization.md) |  | [GetAuthorizationFn](./tencentcloud-cls-uploader-sdk.getauthorizationfn.md) | _(Optional)_ 获取临时密钥函数 |
|  [httpAdapter?](./tencentcloud-cls-uploader-sdk.iclientconfig.httpadapter.md) |  | 'xhr' \| 'http' \| AxiosAdapter | _(Optional)_ http 请求适配器 |
|  [logExpiredDays?](./tencentcloud-cls-uploader-sdk.iclientconfig.logexpireddays.md) |  | number | _(Optional)_ 本地日志清理时间（单位: day, 默认 7 天）（暂未开发） |
|  [logPath?](./tencentcloud-cls-uploader-sdk.iclientconfig.logpath.md) |  | string | _(Optional)_ 本地日志缓存路径，选填（暂未开发） |
|  [maxRetainDuration?](./tencentcloud-cls-uploader-sdk.iclientconfig.maxretainduration.md) |  | number | _(Optional)_ 未上传的缓存日志超过该时间则上传（单位: s，默认 20s） |
|  [maxRetainSize?](./tencentcloud-cls-uploader-sdk.iclientconfig.maxretainsize.md) |  | number | _(Optional)_ 未上传的缓存日志数量超过该数值则上传（默认 30 条） |
|  [onError?](./tencentcloud-cls-uploader-sdk.iclientconfig.onerror.md) |  | (error: [IClsSDKError](./tencentcloud-cls-uploader-sdk.iclssdkerror.md)<!-- -->) =&gt; void | _(Optional)_ 生命周期：上传器发起请求发生错误（不影响上传器后续使用） |
|  [proxy?](./tencentcloud-cls-uploader-sdk.iclientconfig.proxy.md) |  | { host: string; port: number; protocol?: string; } | _(Optional)_ 代理配置 |
|  [region](./tencentcloud-cls-uploader-sdk.iclientconfig.region.md) |  | string | 要上传的CLS地域 |
|  [sourceIp?](./tencentcloud-cls-uploader-sdk.iclientconfig.sourceip.md) |  | string | _(Optional)_ 日志来源，一般使用机器 IP 作为标识 |
|  [topicId](./tencentcloud-cls-uploader-sdk.iclientconfig.topicid.md) |  | string | cls topicId |

