# 修改公司信息
http://api.ilvzan.com/v2/provider/info/companyUpdate
请求：
``` js
{	
	token:"U2FsdGVkX1WH21HHIMymBj5yUg1FueYYUbFHTeojM",
	updateFiled:'Name'
	value:'公司名称’
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
        "message": "error"           //错误信息
     }
]
```

**可以修改的字段名称**

| 字段名|名称|
| :-------- | --------:| 
|Name|公司全称|
|ShortName|公司简称|
|Tel|电话|
|Fax|传真|
|tel|电话|
|Address|地址|
|Intro|公司简介|


