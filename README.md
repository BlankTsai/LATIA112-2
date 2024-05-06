# 國立臺灣師範大學 教育大數據微學程 LATIA112-2
## 學習分析工具實務應用(Learning Analytics Tools Implementation Applications)
廖執善 博士 Tom Liao, 業界講師 Ryan Chung

my info:41271121H 蔡廷軒
***
## HW1

[LATIA_HW1.ipynb](https://github.com/BlankTsai/LATIA112-2/blob/main/HW1/LATIA_HW1.ipynb) 為執行檔案，使用([15y_up_EDU_LV](https://github.com/BlankTsai/LATIA112-2/blob/main/HW1/15y_up_EDU%20LV.csv))作為統計的資料集，使用[matplotlib](https://matplotlib.org/)繪製圖表，程式執行完畢後，圖片會存在同目錄下的[answer_picture](https://github.com/BlankTsai/LATIA112-2/tree/main/HW1/answer_picture)。

```
資料集說明:此資料集為這是一個有關15歲以上教育程度的csv數據,取自政府資料開放平台的數據  
網頁:https://data.gov.tw/dataset/14220
```

### Question:
- 問題一:就讀研究所的人數佔所有人數之比例
- 問題二:15歲到65歲以上就讀大學為最高學歷人數的變化趨勢
- 問題三:65歲以上就讀大學為最高學歷的男女性別比值
- 問題四:總年齡男女不識字比值與65歲以上男女不識字比值之比值
- 問題五:各年齡段就讀高中為最高學歷之人數比較
- 問題六:各年齡段不識字人數之比較
## HW2

### 使用requests
[LATIA_HW2_Request&BTFSoup.ipynb](https://github.com/BlankTsai/LATIA112-2/blob/main/HW2/LATIA_HW2_Request%26BTFSoup.ipynb) 為執行檔案，[LATIA_HW2_ReqwithBTFS.csv](https://github.com/BlankTsai/LATIA112-2/blob/main/HW2/LATIA_HW2_ReqwithBTFS.csv)為爬取的內容。

### 使用selenium
[LATIA_HW2_Selenium.ipynb](https://github.com/BlankTsai/LATIA112-2/blob/main/HW2/LATIA_HW2_Selenium.ipynb) 為執行檔案，[LATIA_HW2_Sel.csv](https://github.com/BlankTsai/LATIA112-2/blob/main/HW2/LATIA_HW2_Sel.csv)為爬取的內容。

```
爬取網頁:104求職網站，並於搜尋欄搜尋關鍵字"科技業"
url:https://www.104.com.tw/jobs/search/?svrd=1&jobsource=cmw_redirect&keyword=%E7%A7%91%E6%8A%80%E6%A5%AD
```

## 爬取內容

* 工作標題
* 工作地點
* 年資要求
* 學歷要求
