```Mermaid
gantt
    title 專案排程甘特圖 (總工期: 155 天)
    dateFormat x
    axisFormat %s

    section 專案實施
    研擬計畫      :crit, 1, 0, 1
    任務分配      :crit, 2, after 1, 4
    取得硬體      :3, after 1, 17
    程式開發      :crit, 4, after 2, 70
    安裝硬體      :5, after 3, 10
    程式測試      :crit, 6, after 4, 30
    撰寫使用手冊  :7, after 5, 25
    轉換檔案      :8, after 5, 20
    系統測試      :crit, 9, after 6, 25
    使用者訓練    :10, after 7, 20
    使用者測試    :crit, 11, after 9, 25
```
