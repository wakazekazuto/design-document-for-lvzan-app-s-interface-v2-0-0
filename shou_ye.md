# 首页
http://api.ilvzan.com/v2/index

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
		identity:'0',          //0是供应商   1是组团社
		stayOrderCount：'8',   //待处理订单数量
		rightamount：'9990',      //账户余额
		unSettleAmount：'9990',   //未结算金额
		unPayAmount：'9990',   //已结算金额 
		freezeAmount:'1234'    //冻结金额 		
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

