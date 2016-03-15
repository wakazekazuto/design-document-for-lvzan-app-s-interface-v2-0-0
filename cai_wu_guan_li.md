# 财务管理

http://api.ilvzan.com/v2/provider/product/indexs

请求：
``` js
{
	curPage:"1", 		//当前页码
	pageSize:"10" ,      //每页显示的条数
	goBeginTime:'1456737174',  //开始出发时间（可选与goEndTime成对）
	goEndTime: '1456537174',   //开始结束时间（可选与goBeginTime成对）
	reserveBeginTime:'1456737174',  //预计出发时间（可选与reserveEndTime成对）
	reserveEndTime: '1456537174',   //预计结束时间（可选与reserveBeginTime成对）
	token:"U2FsdGVkX1WH21HHIMymBj5yUg1FueYYUbFHTeojM"	
}
```

`备注：`
1. 其中goBeginTime、goEndTime、reserveBeginTime、goBeginTime为可选字段，成对出现。不填为空

返回：
``` js
{
	code:"20000",           //返回代码
	message:"all right",    //返回消息
	result:{
		curPage:"1", 		//当前页码
		pageSize:"10"       //每页显示的条数
		totalpayAmount:"50"         //总金额
		totalpersoncount:"222"         //总人数
		data:[ 
			//订单编号
			OrderNum:'P123123'
			//线路名称
			title:'韩国二日游',
			//下单组团社
			travagentshortname：'安徽国旅',
			//出发时间
			startdate：'1451367767',
			//游客人数
			personcount:'23',
			//已收金额
			payAmount:'12331'
		]
	}           
}
```