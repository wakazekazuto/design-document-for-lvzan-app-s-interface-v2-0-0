# 订单列表

http://api.ilvzan.com/v2/group/indent/list
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
			//  
}
```
返回：

``` js
{
	code:"20000",           //返回代码
	message:"all right",    //返回消息
	result:{
		OrderNum：'P000008976'          //订单编号
		data:[ 
			//团队编号
			cravnum:'T0028293',
			//出发日期
			contactname:'1451367767',
			//行程天数
			travdays:'3',
			//线路联系人姓名
			contactname:'科鲁兹'
			//线路联系人手机号
			contactphone:'18944512213',
			//订单编号
			OrderNum:'P000008976',
			//预订时间
			scheduldate:'1451367767',
			//下单账号
			ActName:'组团社体验',
			//支付渠道
			PayType:'乐汇付',
			//经办人姓名
			contact:'夏李娟',
			//经办人手机号
			phone:'18944512213',
			//下单人数
			personcount:'3',
			//供应商-应收金额
			roomamount:'1123',
			//平台立减金额
			returnamount:'23',
			//修改违约金金额
			ModifyTdamages:'12',
			//退团违约金金额
			groupdamages:'31',
			//组团社-应付金额
			totalpatformdiscount:'1134',
			//组团社-已付金额
			payamount:'1100',
			//组团社-未付金额
			totalrunwayfee:'21'
		]
	}
}
```