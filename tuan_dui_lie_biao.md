# 团队列表
http://api.ilvzan.com/v2/provider/product/list
``` js
{
	curPage:"1", 		//当前页码
	pageSize:"10"       //每页显示的条数
	title："",          //团队名称为空代表全部
	cravnum："",        //团队编号为空代表全部
	status："",        //状态为空代表全部
	departuredateBegin："1473235235",  //出发时间 为空代表全部
	departuredateEnd："1473235235",  //结束时间 为空代表全部
	productnum：'15535',  //线路编号
	token:"U2FsdGVkX1WH21HHIMymBj5yUg1FueYYUbFHTeojM"
}
```

返回：
``` js
{
	code:"20000",           //返回代码
	message:"all right",    //返回消息
	result:{
		totalPage:12,	//	int	总页数
		pageSize:10,	//	int	每页显示的条数
		curPage:1,		//	int	当前页码
		title:'青岛双飞三日游',  //线路名称
		data:[
			{
				cravnum:'http://i.ilvzan.com/head1.jpg',    //团队编号
				departuredate:'1451367767',                 //出发日期（时间戳）
				seatcount:'10',                             //计划座位数
				alreadySeatcount:'8',				        //已售座位数
				residueSeatCount:'2',                       //剩余座位数
				//团队状态  （0销售中 1已经暂停 2已确定）
				status:'0',
				//团期已过状态（0过期 1正常）
				past:'0'
			},
			{
				cravnum:'http://i.ilvzan.com/head1.jpg',
				departuredate:'1451367767',
				seatcount:'10',
				alreadySeatcount:'8',
				residueSeatCount:'2',
				status:'0',
				past:'0'
			}
		]
	}
}
```

**备注**

status 状态
| 标识|简介|
| :-------- | --------:| 
|-1|删除|
|0|暂停|
|1|正常|
|2|乐游审批|
|3|组团社审批|
|4|确定|
|5|锁定|


