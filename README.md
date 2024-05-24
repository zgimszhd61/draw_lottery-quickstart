# draw_lottery-quickstart
```
import random

def draw_lottery(names):
    # 随机选择并返回列表中的一项
    return random.choice(names)

# 用户输入名单
names = [
"@aaa",
"@bbb",
"@ccc",
"@ddd",
]


# 进行抽奖
winner = draw_lottery(names)
print(f"恭喜 {winner} 获得了奖品！")

```
