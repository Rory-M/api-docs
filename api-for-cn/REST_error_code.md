# 错误代码
code = 200，表示请求成功，其它均为错误，错误码请参考以下表格：

| 错误码 | 说明 |
| ------ | ------ |
| -1001 | 请求超出限制，如果没有API_KEY，请尽快[申请API_KEY](/api-for-cn/signup_app_key.md) |
| -1002 | API_KEY不正确 |
| -1003 | 签名错误，请参考[签名认证](/api-for-cn/REST_authentication.md) |
| -1004 | 请求的时间戳已过期 |
| -1005 | 没有权限，请求交易和订单API需要验证API_KEY |
| -1101 | account格式不正确 |
| -1102 | email格式不正确 |
| -1103 | symbol不正确 |
| -1104 | trx_id不正确 |
| -1105 | 订单已被取消 |
| -1106 | 订单已被成交，不能取消 |
| -1500 | 未知错误 |
