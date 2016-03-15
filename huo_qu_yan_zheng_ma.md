# 获取验证码
http://api.ilvzan.com/v2/mobileCodeGet
请求：
``` js
{
	"mobile":"18949554415"   //手机号码
```

返回：
``` js
//成功
[
    {
        "code": "20000",
        "message": "all right"，
        "retult":{
            "message":"123123"       //验证码
        }     
    }
]

//失败
[
    {
        "code": "410002",        //错误代码
        "message": "invalid code"        //错误信息
     }
]
``` 
