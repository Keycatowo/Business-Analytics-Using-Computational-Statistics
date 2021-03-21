# R-基本指令
#R 


## 幫助


##### 查看函數document
```R
# Type 1 
?FUNCTION()
# Type 2
help(FUNCTION)
```

##### 查看operator的document
```R
# 例如查看`:`符號
?`:`
```


##### 查看參數
```R
args(FUNCTON)
```



## 檔案

##### 列出目前路徑
```R
getwd()
```

##### 列出目前目錄的檔案
```R
# Type 1 顯示所有檔案
ls()
# Type 2 只顯示R相關檔案
list.files() 
```

##### 建立資料夾
```R
dir.create(path="$dir_name", recursive=TRUE)
```
+ recursive:如果需要建立嵌套的資料夾的話就必須要打開

##### 檢查檔案是否存在
```R
file.exists("$file_name")
# 回傳為 TRUE/FALSE
```

##### 查看檔案資訊
```R
file.info("$file_name")
```

![[Pasted image 20210228075335.png]]


##### 更改檔案名稱
```R
file.rename(from="$$old_name",to="$new_name")
```


##### 複製檔案
```R
file.copy(from="$$old_path",to="$new_path")
```


##### 顯示檔案路徑
```R
# just one file
file.path("file_name")
# or you can concat them 
file.path("folder1","folder2")
```
> 使用`file.path()`的好處是可以在不受到不同作業系統影響的情況下產生同樣結果的路

##### 變更工作路徑
```R
setwd("$path")
```



## 查詢

##### 查詢變數類型
```R
class(var)
```

##### 查詢函式參數
```R
args(fun)
```



##### 查詢函式記憶體
```R
tracemem(fun)
```