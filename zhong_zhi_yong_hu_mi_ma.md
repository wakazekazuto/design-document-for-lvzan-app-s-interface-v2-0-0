# 重置用户密码
请求路径：http://api.ilvzan.com/v2/login/resetpwd
``` js
{
	token:"U2FsdGVkX1WH21HHIMymBj5yUg1FueYYUbFHTeojM",
	oldpwd:"123123",   //旧的密码base32格式
	newpwd:"112233"    //新的密码base32格式
}
```

返回：
``` js
//成功
{
	code:"20000",           //返回代码
	message:"all right"
}

//失败
{
	code:"41003",           //返回代码
	message:"error pwd"     //旧密码不正确
}
```
