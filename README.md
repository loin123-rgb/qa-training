# QA 教育訓練

新進品保人員的流程訓練教材。

📖 **網站:<https://loin123-rgb.github.io/qa-training/>**

## 這是什麼

給新進 QA 人員的自學 / 帶訓教材,目標是三個月後能獨立執行檢驗、做出判定、處理不合格品,並且**知道自己什麼時候不該判**。

跟「操作說明書」的差別:說明書講怎麼做,這份教材講**為什麼這樣規定**。新人只會照抄表單的話,遇到例外就會當機。

## 章節

| 章節 | 內容 | 時數 |
|:--|:--|:--|
| [品保的進化史](https://loin123-rgb.github.io/qa-training/history/) | 六個紀元、五句口號 — 這些規定是怎麼來的 | 40m |
| [第一章 · 基礎](https://loin123-rgb.github.io/qa-training/basics/) | 品質關卡全貌、名詞對照 | 2h |
| [第二章 · IQC 進料檢驗](https://loin123-rgb.github.io/qa-training/iqc/) | 流程、抽樣計畫、判定與填表 | 6h + 實作 |
| [第三章 · 成品測試](https://loin123-rgb.github.io/qa-training/testing/) | 測試流程、流量點與誤差限、校正設定點 | 6h + 實作 |
| [第四章 · 不良品與矯正措施](https://loin123-rgb.github.io/qa-training/ncr/) | 不合格品處置、矯正措施與 8D | 4h |
| [自我檢核](https://loin123-rgb.github.io/qa-training/checklist/) | 30 / 60 / 90 天檢核表 | — |
| [公司手冊](https://loin123-rgb.github.io/qa-training/handbook/) | 品檢組實際編製的三份手冊:進料檢驗、製程巡檢、彙整資料與邏輯分析 | 依手冊 |

## 公司手冊區

`handbook/` 收錄品檢組實際編製的手冊,由 Word 原檔自動轉換,**內容未經改寫**。
公開版已移除內部系統操作截圖(含登入者姓名與內部系統資訊)。

## 重要聲明

> 本教材是**通用性訓練內容**,用來建立觀念與判斷邏輯。
>
> 實際的抽樣水準、AQL 值、允收基準、表單版次、簽核層級,一律以**公司核發的最新管制文件**為準。兩者不一致時以管制文件為準。
>
> 教材裡的數字(批量、樣本數、誤差值、供應商名稱)全部是**示範用的假資料**,不可作為實際判定依據。

## 維護

新增或修改章節後推上 `main`,GitHub Pages 會自動重建。

流程圖用 [Mermaid](https://mermaid.js.org/),直接寫在 ` ```mermaid ` 區塊裡。

本機預覽:

```bash
bundle exec jekyll serve
```

## 授權

教材內容供內部教育訓練使用。
