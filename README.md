# 政附資訊 社課實作示範

> Created by 王修佑 (GitHub [@WHY-Hugo](https://github.com/WHY-Hugo))<br>
> [HackMD](https://hackmd.io/@hwang05/rkMEGXnH9?openExternalBrowser=1)
### 2022/04/29 社課X 
## Gantt

👉[開啟雙欄模式檢視原始語法](https://hackmd.io/T-UpzCz-QV-AMSDCmXIVUw?both)

````
```mermaid
gantt
%% 宣告圖表樣式gantt
    title 甘特圖 社課範例
		%% 圖表標題
    dateFormat  MM-DD
		%% 日期格式
		axisFormat  %m-%d
		%% 縱軸的日期格式
		
		section 前期工作
		%% 宣告一個區塊
		    Conceive project : crit, done, plan, 04-11, 28d
			%%語法：
			%%甘特圖上的任務名稱 : [crit], [active|done], 任務名稱, [日期|after 任務名稱], 長度

		
        section 預處理
            Rlated Work  :active,bb, 05-02, 42d
            Collection & extend datasets  : crit ,b2, 05-09, 56d
    
		section 主要工作
            Data preprocessing: active, dp, 06-13  , 35d
            Model tuning: implement, after dp, 63d

		section 研究收案
			Analysis & Evaluation: copyright, 07-25, 70d
            Discussion & conlcusion: dc, 08-08, 72d
			
        section 發表工作
            Writing & Modify report: wm, 09-05, 49d
            Presentation: milestone, after wm, 7d
```
````

```mermaid
gantt
%% 宣告圖表樣式gantt
    title 甘特圖 社課範例
		%% 圖表標題
    dateFormat  MM-DD
		%% 日期格式
		axisFormat  %m-%d
		%% 縱軸的日期格式
		
		section 前期工作
		%% 宣告一個區塊
		    Conceive project : crit, done, plan, 04-11, 28d
			%%語法：
			%%甘特圖上的任務名稱 : [crit], [active|done], 任務名稱, [日期|after 任務名稱], 長度

		
        section 預處理
            Rlated Work  :active,bb, 05-02, 42d
            Collection & extend datasets  : crit ,b2, 05-09, 56d
    
		section 主要工作
            Data preprocessing: active, dp, 06-13  , 35d
            Model tuning: implement, after dp, 63d

		section 研究收案
			Analysis & Evaluation: copyright, 07-25, 70d
            Discussion & conlcusion: dc, 08-08, 72d
			
        section 發表工作
            Writing & Modify report: wm, 09-05, 49d
            Presentation: milestone, after wm, 7d
```
### 👍好站推薦
- [如何繪製甘特圖](https://hackmd.io/@hackmd-marketing/draw-gantt?utm_source=twitter&utm_medium=post-link)
- [Mermaid.js document](https://mermaid-js.github.io/mermaid/#/gantt?id=syntax)

## Pie Chart
👉[開啟雙欄模式檢視原始語法](https://hackmd.io/T-UpzCz-QV-AMSDCmXIVUw?both)
````
```mermaid
pie

title Animals

"Dogs" : 52.8
"Cats" : 24.8
"Rats" : 8.6
"Dragon" :  4.0
"Lion": 8.9
```
````

```mermaid
pie

title Animals

"Dogs" : 52.8
"Cats" : 24.8
"Rats" : 8.6
"Dragon" :  4.0
"Lion": 8.9
```
### 👍好站推薦
- [畫圖真的好簡單](https://hackmd.io/c/tutorials-tw/https%3A%2F%2Fhackmd.io%2F%40docs%2Fmermaid_pie?fbclid=IwAR0dQVb-373PL-57PhsdOWoOFYgh2j1JrA78hwTzD6NP92q6XY90X9jD5g0)

