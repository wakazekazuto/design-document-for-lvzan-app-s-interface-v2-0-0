# 公司信息

http://api.ilvzan.com/v2/provider/info/company
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
		data:[
			Name:"马鞍山青年国际旅行有限责任公司", //公司全称
			ShortName:"马鞍山青年国际",//公司简称
			Tel:"0553-3239123",//电话
			Fax:"0553-3239123",//传真
			Address:"马鞍山青年国际旅行有限责任公司",//公司地址
			//公司简介
			Intro:"马鞍山青年国际旅行有限责任公司马鞍山青年国际旅行有限责任公司马鞍山青年国际旅行有限责任公司",
			//经营目的地省份和旗下景点
			province:{
				[provinceName:"安徽",Operatename:"九华山、天堂寨、天柱山"],
				[provinceName:"江苏",Operatename:"珍珠湖、中山陵、总统府"],
			},
			//客服
			service:{
				//某类型的服务商
				[
					TypeName:"专线服务商",
					//0代表禁用，1代表启用
					State:"0",
					customer:{
						//0代表禁用，1代表启用
						[CusName:"小花",Tel:"0553-3239123",QQ:"45932262",Phone:"1895944335",State:'0'],
						[CusName:"小乐",Tel:"0553-3239123",QQ:"459322602",Phone:"1895944335",State:'1']
					}
				],
				[
					TypeName:"组团旅行社",
					State:"0",
					customer:{
						[CusName:"小花",Tel:"0553-3239123",QQ:"45932262",Phone:"1895944335",State:'0'],
						[CusName:"小乐",Tel:"0553-3239123",QQ:"459322602",Phone:"1895944335",State:'1']
					}
				]
			}
		]
	}
}
``` 