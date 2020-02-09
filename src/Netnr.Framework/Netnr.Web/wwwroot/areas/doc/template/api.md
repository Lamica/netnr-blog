﻿ **简要描述：**

- 用户注册接口

**请求URL：** 
- `http://xx.com/api/user/register`
  
**请求方式：**

- POST

**参数：**

|参数名|必选|类型|说明|
|:----|:----:|:-----|:-----|
|username |是 |string |用户名 |
|password |是 |string |密码 |
|name |否 |string | 昵称 |

 **返回示例**

``` 
  {
    "error_code": 0,
    "data": {
      "uid": "1",
      "username": "12345",
      "name": "汤姆",
      "sex": 2 ,
      "reg_time": "1436865212"
    }
  }
```

 **返回参数说明** 

|参数名|类型|说明|
|:-----|:-----|-----|
|sex |int |性别编码，1：男；2：女 |

 **备注** 

- 更多返回错误代码请看首页的错误代码描述