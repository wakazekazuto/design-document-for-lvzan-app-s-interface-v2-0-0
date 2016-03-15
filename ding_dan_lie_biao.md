# 订单列表

http://api.ilvzan.com/v2/provider/indent/list
请求：
``` js
{
	curPage:"1", 		//当前页码
	pageSize:"10" ,      //每页显示的条数
	newstatusCode："PayPartLeavRefund",
	token:"U2FsdGVkX1WH21HHIMymBj5yUg1FueYYUbFHTeojM"
}
```
返回：

``` js
{
	code:"20000",           //返回代码
	message:"all right",    //返回消息
	result:{
		curPage:"1", 		//当前页码
		pageSize:"10"       //每页显示的条数
		state：'1'          //状态编号
		data:[ 
			//订单编号
			OrderNum:'P000008976',
			//预订日期:'',	
			scheduldate:'1451367767',	
			//线路图片
		    ImageUrl:'http://i.ilvzan.com/head1.jpg',	
			//线路名称
			title:'韩国二日游',	
			//出发时间
			startdate:'1451367767',	
			//下单组团社简称
			travagentshortname:'测试组旅行社',	
			//下单人数
			personcount:'5',	
			//行程天数
			travdays:'6',	
			//订单总金额
			OrderAmount:'1123.98',	
			//已付金额
			payAmount:'112'	
		]
	}           
}
```