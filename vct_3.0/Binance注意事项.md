> endpoint:https://api.binance.com
> 返回数据为JSON格式
> 数据为降序排序
> 时间单位为ms
# 错误信息
- 403:WAF(Web Application Firewall)的原因被屏蔽
- 429:超出最高访问频率
- 418:在收到429之后仍然不断访问
- 5XX:Internal Servet Error

# 请求方式
- GET使用query string
- POST使用query string或request body(header content type被标记为application/x-www-form-urlencoded)


