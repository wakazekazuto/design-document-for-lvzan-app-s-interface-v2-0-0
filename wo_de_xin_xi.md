# 我的信息

http://api.ilvzan.com/v2/provider/info
请求：
``` js
{
	token:"U2FsdGVkX1WH21HHIMymBj5yUg1FueYYUbFHTeojM"
}
```
返回：
``` js
[
    {
        "code": "20000",
        "message": "all right",
        "result": {
            "address": "观澜路1号滨江商务楼16楼",//居住地址
            "departmentname": "技术部", //部门 
            "email": "316960074@qq.com",  //邮箱
            "fox": "",          //传真号
            "idCard": "342601198712124024", //身份证号
            "mobile": "15255334943",   //手机号
            "phonenum": "15255334943", //手机号
            "positionname": "测试",  //职位名称
            "isbind":'0',//是否绑定手机
             "qq": "316960074",   //QQ
            "realName": "测试供应商",   //真实姓名
            "remarks": "",   
            "sex": "女",     //性别
            "tel": "0553-2793000"  //电话
        }
    }
]
```
失败：

``` js
{
	code:"41001",    //错误代码
	message:"content missing"
}
```