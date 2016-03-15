# 个人信息

http://api.ilvzan.com/v2/info/personal
请求：
``` js
{
	token:"U2FsdGVkX1WH21HHIMymBj5yUg1FueYYUbFHTeojM"
}
```
返回：
``` js
[
    {
        "code": "20000",
        "message": "all right",
        "result": {
            "company": "体验账号",  //公司名称
            "imgUrl": "http://res.ilvzan.com/Content/Default/75x73.jpg",  //头像地址
            "loginName": "G0553jsce"  //帐号名称
        }
    }
]
```
失败：

``` js
{
	code:"41001",    //错误代码
	message:"content missing"
}
```