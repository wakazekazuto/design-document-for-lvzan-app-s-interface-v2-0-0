# 线路列表
http://api.ilvzan.com/v2/provider/product/index

``` js
{
	curPage:"1", 		 //当前页码
	pageSize:"10" ,      //每页显示的条数
	title:'',            //线路名称（可以为空代表全部）
	productnum:''，      //线路编号（可以为空代表全部）
    lineTypeName：''，   //线路类型（空代表全部）
    issueFlag：''，      //发布类型（空代表全部）
    status:'',          //状态（空代表全部）
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
		data:[
			{
				ImageUrl:'http://i.ilvzan.com/head1.jpg',//线路图片		
				title:'青岛双飞三日游',//线路名称
				productnum:'15535',//线路编号
				alreadyStravCount:'1',	//已开班期数量
				residueStravCount:'6' //剩余的班期数量
			},
			{
				ImageUrl:'http://i.ilvzan.com/head1.jpg',
				title:'青岛双飞三日游',
				productnum:'15535',
				alreadyStravCount:'1',
				residueStravCount:'6'
			}
		]
	}
}
```


备注：

1.线路类型分类

| 标识|简介|
| :-------- | --------:| 
|personal|散客班|
|reception|地接团|
|through|直通车|

2.issueFlag  发布类型分类

| 标识|简介|
| :-------- | --------:| 
|0|散拼|
|1|地接|
|2|定制|

3. status 状态

| 标识|简介|
| :-------- | --------:| 
|-1|删除|
|0|暂停|
|1|正常|
|2|乐游审批|
|3|组团社审批|
|4|锁定|

