# 反馈

http://api.ilvzan.com/v2/info/insert

`图片接口`上传需要调试，目前还没有测过插件成功情况
请求：
``` js
{
	token:"U2FsdGVkX1WH21HHIMymBj5yUg1FueYYUbFHTeojM",
	phone："18949554415"              //联系方式（非必须）,
	content："我是反馈意见"                       //小于150个字
	pic:[]           //图片
}
```

返回：
``` js
{
	code:"20000",           //返回代码
	message:"all right",    //返回消息	
}
```

失败：
``` js
{
	code:"41001",    //错误代码
	message:"content missing"   //错误类型
}
```