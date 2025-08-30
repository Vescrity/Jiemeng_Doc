# 程序配置

## 配置文件

【待补充】

1. 配置Jiemeng相关配置[config.json]
	- (可参考预设文件)

    | 字段          | 类型     | 说明                                        | 默认值                   |
    | ------------- | -------- | ------------------------------------------- | ------------------------ |
    | self_id       | string   | bot qq号                                    | 0                        |
    | port          | int      | WebSocket端口                               | 必填                     |
    | Debug_Mode    | bool     | 是否启用Debug日志信息显示                   | false                    |
    | private_black | bool     | 私聊名单(private_list)是否作为黑名单        | true                     |
    | admin_list    | object   | 管理员列表<br/>"QQ号(string)":管理等级(int) | 无默认，需保证类型正确   |
    | private_list  | string[] | 私聊名单                                    | 无默认，需保证类型是数组 |
    | black_list    | string[] | 全局黑名单                                  | 无默认，需保证类型是数组 |
    | group_list    | string[] | 群聊白名单                                  | 无默认，需保证类型是数组 |
		- `Custom_Config`
  		- 任意自定义量。
  		- 词库中所有形如 `{~...}` 的字符串会被替换为其对应的 `Custom_Config` 中设定的值。
  		- 例如你在 `Custom_Config` 中设定了 `"test": "1234"` ，那么你词库中所有的 `{~test}` 都会被替换为 `1234`

