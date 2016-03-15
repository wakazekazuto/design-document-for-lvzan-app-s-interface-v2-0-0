# 版本更新

http://api.ilvzan.com/v2/info/version

请求：
``` js
{
	token:"U2FsdGVkX1WH21HHIMymBj5yUg1FueYYUbFHTeojM",
	newVersion："V1.0"   //设置版本号（非必须）
}
```
返回：
``` js
{
	code:"20000",           //返回代码
	message:"all right",    //返回消息
	result:{
		"version":"V1.0"  //版本号	
	}
}
```

失败：
``` js
{
	code:"41003",    //错误代码
	message:"invalid pwd"
}
```