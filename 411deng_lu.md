# 4.1.1.登录

请求路径：http://api.ilvzan.com/v2/access_token
``` js
{
	ActName:"1861602608", 		
	password:" 07dd67e1ac39da80062d3125b512d822" 
}
```

返回：
``` js
{
	code:"20000",           //返回代码
	message:"all right",    //返回消息
	result:{
		token:"U2FsdGVkX1WH21HHIMymBj5yUg1FueYYUbFHTeojM",
		identity:'0'        //0是供应商   1是组团社
	}	
}
```