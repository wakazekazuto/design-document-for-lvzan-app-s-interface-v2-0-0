# 我的信息修改
http://api.ilvzan.com/v2/provider/infoUpdate
请求：
``` js
{
	token:"U2FsdGVkX1WH21HHIMymBj5yUg1FueYYUbFHTeojM",
	updateField:'address'，   //需要修改的字段名
	value:'芜湖市镜湖区观澜路1号'
}
```

返回：
``` js
成功
[
    {
        "code": "20000",
        "message": "all right"
     }
]

失败
[
    {
        "code": "410003",            //错误代码
        "message": "error"       //错误信息
     }
]
```

**可以修改的字段名称**

| 字段名|名称|
| :-------- | --------:| 
|realName|真实姓名|
|sex|性别|
|idCard|身份证号|
|mobile|手机|
|tel|电话|
|fox|传真|
|qq|QQ|
|departmentname|部门|
|positionname|职务名称|
|address|地址|
|remarks|备注|


