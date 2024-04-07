# python

## 次標題
```python
def hw1_0():
    string1 = "小明花105元買了蘋果"
    string2 = "小華花130元買了香蕉"
    #-------------------------------
    # 注意cost為字串(string)的型別
    # cost = # ...
        price1=int(string1[3:6])
        price2=int(string2[3:6])
        total_price=price1+price2
        cost=str(total_price)
    #-------------------------------
    return "小明和小華共花了" + cost + "元買水果"
```
```python
def hw1_1():
    str1 = "abcdefghijk"
    output = ""
    #-------------------------------
    output += str1[0:2]
    output += str[2]*4
    output += str1[3]
    output +=str1[8:10]
    output +=str1[10]*2
    output +=str[7]*2
    #-------------------------------
    return output
```
```python
def hw1_2():
    output = 0
    #-------------------------------
    # output = # ....
    max_voltage=10
    min_voltage=-10
    resolution=14
    min_measurable_voltage=(max_voltage-min_voltage/(2**resolution))
    output=min_measurable_voltage

    #-------------------------------
    return output
```
```python
    def hw1_3():
    output = ""
    #-------------------------------
    # output = # ....
    for a in range(2,10):
        for b in range (2,10):
            print(f"{a}*{b}={a*b})
        print("==")
    #-------------------------------
    return output
```