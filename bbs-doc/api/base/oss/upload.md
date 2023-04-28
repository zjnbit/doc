##### 简要描述

- 注册

##### 请求URL
- ` /api/oss/upload `

##### 请求方式
- PUT

##### 参数

| 参数名      |必选| 类型     | 说明              |
|:---------|:---|:-------|-----------------|
| file     |是  | file   | 文件              |
| password |是  | string | 明文密码进行md5散列(小写) |
| email    |是  | string | 邮件地址            |
| code     |是  | string | 注册验证码           |
| nickname |是  | string | 昵称              |

##### 返回示例

````json
{
  "errCode": "00000",
  "errMsg": "操作成功",
  "data": {
    "bucket": "bbs",
    "size": 130119,
    "lastModified": "2023-04-28T17:48:29+08:00",
    "region": null,
    "contentType": "image/png",
    "key": "20230428/c6d0220ebc64427fb31a9e52d8a0c251.png"
  },
  "time": "2023-04-28 17:48:29",
  "requestId": "7a16f53f-c5e0-4bc0-8305-39a40b393aec"
}
````

##### 返回参数说明

|参数名|类型|说明|
|:-----  |:-----|-----                           |
| |   |  |

##### 备注

- 更多返回错误代码请看首页的错误代码描述




