# 返回码详细定义

| 返回码|状态码描述|说明
| :-------- | --------:| --------:|
|20000|all right|验证通过| 
|40001|token missing|缺失token参数| 
|40002|username missing|缺失username参数| 
|40003|pwd missing|缺失pwd参数| 
|41001|invalid token|错误的token|
|41002|invalid username|不存在的用户名|
|41003|invalid pwd |错误的密码|
|41004|invalid field|错误的字段|
|41005|invalid code|错误的验证码|
|42001|token expired|access_token超时|	
|43001|require GET method|需要使用GET方法|	
|43002|require POST method|需要使用POST方法|
|44001|empty content	|空白的内容|
|44002|empty list size	|空白的列表|
|45001|	api limit|频率限制|
|50001|api unauthorized|接口未授权|
