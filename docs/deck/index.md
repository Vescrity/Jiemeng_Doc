# Deck 模块 (Dice! 牌堆)

将所有牌堆文件放入 deck 文件夹中。将如下的应答组放入应答库中，即可通过 `.draw#...` 来调用牌堆。

```json
{
      "regex": "^\\.draw#",
      "anss":[
        {"lua_call": "mapi.bot.draw_deck"}
      ],
      "pri": 105
}
```
- 注意：并不完全兼容。需要对牌堆内部分特殊文本(如`{nick}`进行替换)

> [!WARNING]
> 调用方式可能随版本变化更改！

