# 用户名判断

请求路径：http://api.ilvzan.com/v2/login/username
``` js
{
	ActName:"1861602608"
}
```

返回：
``` js
{
	code:"20000",           //返回代码
	message:"all right",    //返回消息
	result:{
		exist:0,             //0是不存在    1是存在
		identity:'0',        //0是供应商    1是组团社
		isbind:'1'           //0代表没绑定  1代表绑定
	}	
}
```

失败：
``` js
{
	code:"45001",    //错误代码
	message:"api limit"  //接口请求过多
}
```
