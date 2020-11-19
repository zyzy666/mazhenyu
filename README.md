# 马振宇

## 软工2班

### 学号2020012132



**“我对信息素养实践课的认识”**

*在我看来信息素养课对于我们学软件工程的同学们来说，是一门非常重要的辅助类课程*

*它交给我们如何正确的使用我们的电脑，以及计算机的更多操作及使用，*

*它详细完整的为我们介绍了各类软件工程专业上，以及未来的生活中我们会用到的软件及操作系统，是我们这个专业必不可少的一门课程。*

*它可能不像其他课程一样有那么多理论性的知识，但是它的含金量一样很高，它注重的是实践和操作，也需要我们好好地学习，更需要我们好好地练习，它不是很难，当然，是你认真学的前提下，如果不听课，不操作，它也会让你难堪，总之，我认为信息素养实践课是一门非常有用也值得我们学习的课程。*

[链接](www.baidu.com)





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