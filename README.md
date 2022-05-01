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
        section 研究發表
            Writing & Modify report: wm, 09-05, 49d
            Presentation: milestone, after wm, 7d
```
