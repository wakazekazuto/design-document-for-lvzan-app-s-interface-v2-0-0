# 修改绑定手机

http://api.ilvzan.com/v2/bindMobileUpdate

请求：
``` js
{
	"token":"U2FsdGVkX1WH21HHIMymBj5yUg1FueYYUbFHTeojM",
	"newmoblie":'18949554415',   //需要修改的字段名
	"code"：'128911'             //获取的验证码
}
```


返回：
``` js
//成功
[
    {
        "code": "20000",
        "message": "all right"
     }
]

//失败
[
    {
        "code": "410002",                //错误代码
        "message": "invalid code"       //错误的验证码
     }
]
```
