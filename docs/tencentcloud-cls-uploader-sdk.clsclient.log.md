<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [tencentcloud-cls-uploader-sdk](./tencentcloud-cls-uploader-sdk.md) &gt; [ClsClient](./tencentcloud-cls-uploader-sdk.clsclient.md) &gt; [log](./tencentcloud-cls-uploader-sdk.clsclient.log.md)

## ClsClient.log() method

写入日志

**Signature:**

```typescript
log(log: Record<string, any>, _immediate?: boolean): void;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  log | Record&lt;string, any&gt; | 要上传的日志键值对 |
|  \_immediate | boolean | _(Optional)_ |

**Returns:**

void

## Example


```
 立即上报：clsclient.log({ key: 'value' }, true);
 客户端控制上报：clsclient.log({ key: 'value' });
```

