# 马振宇

```python
print（"hello,world"）
```

```python
print("欢迎使用算数自测小程序，测试开始")
import random
count = 0
right = 0
op = ['+','-','*','/']
z=1
while z<=10:
    a= random.randint(1,10)
    b= random.randint(1,10)
    s = random.choice(op)
    print('%d %s %d = ' %(a,s,b))
    question = input(':')
    if s == '+':
        result = a + b
    if s == '-':
        result = a - b
    if s == '*':
        result = a * b
    if s == '/':
        result = a /b
    if question == str (result):
        print('✓')
        right += 1
    else:
        print('❌,正确答案为',result)
        count += 1
    z+=1

n=10*right
print('您本次测试最终得分为%d'%(n))
```



| 学号 | 语文成绩 | 数学成绩 |
| ---- | -------- | -------- |
| 001  | 85       | 93       |
| 002  | 85       | 93       |
| 003  | 85       | 93       |

1. xin
2. xi
3. su
4. yang

- xin
- xi
- su
- yang
