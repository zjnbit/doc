##### 简要描述

- 注册

##### 请求URL
- ` /api/oauth/signup `

##### 请求方式
- POST

##### 参数

|参数名|必选|类型| 说明              |
|:----    |:---|:----- |-----------------|
|username |是  |string | 用户名             |
|password |是  |string | 明文密码进行md5散列(小写) |
|email |是  |string | 邮件地址            |
|code |是  |string | 注册验证码             |
|nickname |是  |string | 昵称              |

##### 参数示例
````json
{
  "username": "username",
  "password": "12345678901234567890123456789012",
  "email": "user@zjnbit.com",
  "code": "000000",
  "nickname": "nickname"
}
````
##### 返回示例

````json
{
  "errCode": "00000",
  "errMsg": "操作成功",
  "data": {
    "userId": "1651879883728654338",
    "nickname": "nickname",
    "token": "87069cd8-0935-4d8d-a7b9-2f45083a1bab",
    "tokenKey": "zjnbit_bbs_auth"
  },
  "time": "2023-04-28 17:23:49",
  "requestId": "f42edfd5-20ea-4779-a4f1-3bd9a0275f63"
}
````

##### 返回参数说明

|参数名|类型|说明|
|:-----  |:-----|-----                           |
| |   |  |

##### 备注

- 更多返回错误代码请看首页的错误代码描述




