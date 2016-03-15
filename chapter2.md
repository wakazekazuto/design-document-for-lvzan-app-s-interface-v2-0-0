# 2.接口数据格式定义

请求URL：http://api.ilvzan.com/v2/controller/action/access_token

- URL组成：接口地址+请求路径+密钥字符串
- 参数以数组形式提交(POST)
- 返回结果为json字符串

示例：http://api.ilvzan.com/v2/api/indent/index/07dd67e1ac39da80062d3125b512d822
请求参数格式：
``` js
{
	param1:value1,
	param2:value2
	...
	...
}
```

返回格式:
``` js
{
	code:
	message:
	result:{
		totalPage:12,	//总页数
		pageSize:10,	//每页显示的条数
		curPage:1,		//当前页码
		data:[{},{},{}]	//数据
	}
}
```