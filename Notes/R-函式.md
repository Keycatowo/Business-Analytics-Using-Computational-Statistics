# R-函式

#R 

## 函式
### 建立

##### 回傳為最後一行
```R
boring_function <- function(x) {
  x
}
```

##### 支援參數預設值
```R
remainder <- function(num, divisor=2) {
  num %%divisor
}
```

##### 參數可以傳入函數(pass a function as an argument)
```R
evaluate <- function(func, dat){
  func(dat)
}
```

### 不定參數



### 呼叫

##### R支援參數部分匹配
```R
# 以下兩者效果相同
remainder(divisor=11,num=5)
remainder(div=11,num=5)
```

##### 查詢參數
```R
args(remainder)
# function (num, divisor = 2) 
# NULL
```

## 匿名函式

##### 匿名函式格式
```R
function(x){x+1}
```