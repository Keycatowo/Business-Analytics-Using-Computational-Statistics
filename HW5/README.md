# HW5

+ [Questions Document](https://docs.google.com/document/d/1i2no-2rNlEU79c0F8eVFWRZVtPeAG-sUKsp1xEHdEus/edit)

## 重點整理(統計)
### 區間估計
以本次題目的2-b-ii為例
> Estimate the population mean, and the 99% confidence interval (CI) of this estimate

我們看到的1687筆資料是樣本，題目要求我們根據這些樣本去估計母體的平均值是怎樣  
也就是說，我們通過觀察這些樣本得到了樣本的平均數x bar,但是要去估計母體的平均值μ
這個時候根據樣本的這些資料的統計值(樣本標準差s，樣本數量n，樣本平均值xbar)，以及對母體資料掌握程度的選擇——這邊因為不知道母體的標準差是多少，所以在估計平均值的時候採用t分佈

#### 區間估計整理
##### 單一母體
![](img/區間估計(單一母體).png)

##### 兩母體
![](img/區間估計(兩母體).png)


## 失敗記錄(有空再嘗試)
### 雙y軸
這次原本有想要嘗試用ggplot的雙y軸，但是嘗試了很多次之後發現都還是沒有辦法很成功

### 配色方案
原本看到`ggthemr`套件可以用來自動設定ggplot的配色  
但是好像原作者後來沒有在維護了  
嘗試了一些安裝方式(devtools, rtools...等)後來還是沒找到可以使用的方式


## 延伸資料
+ [How to add mean, and mode to ggplot histogram?](https://stackoverflow.com/questions/47000494/how-to-add-mean-and-mode-to-ggplot-histogram)
