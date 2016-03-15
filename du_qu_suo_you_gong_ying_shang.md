# 读取所有供应商

http://api.ilvzan.com/v2/provider/providerName
请求：
``` js
{
	token:"U2FsdGVkX1WH21HHIMymBj5yUg1FueYYUbFHTeojM"
}
```

返回：
``` js
{
	code:"20000",           //返回代码
	message:"all right",    //返回消息
	result:{
		data:{
			[ name:'华夏旅行社',id:123],
			[ name:'华夏旅行社',id:123],
			[ name:'华夏旅行社',id:123]
		}
	}
}
``` 