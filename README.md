# DBA 博士論文模板 — 質性個案研究法

> **授權**：CC BY-NC-ND 4.0（姓名標示-非商業性-禁止改作）
> **作者**：石頭哥｜元智大學管理學院 DBA 博士生
> **版本**：v1.0 | 2026-06-22

本模板為管理學院 DBA 博士生設計，提供一套完整的質性個案研究論文架構。整合以下方法論資源：

- **方法論**：Yin (2018) 個案研究法 + Eisenhardt (1989) 理論建構
- **寫作品質**：AMJ（Academy of Management Journal）編輯群審查標準
- **分析工具**：CIMO 框架（Context-Intervention-Mechanism-Outcome）
- **流程分析**：Langley (1999) 過程資料分析法

## 誰適合使用？

- 管理學院 DBA / PhD 研究生，採用質性個案研究法
- 研究主題涉及：組織轉型、策略變革、技術路徑選擇、生態系競爭等
- 需要一套可複用的訪談文件、蒸餾卡、操作手冊

## 目錄結構

```
dba-thesis-template/
├── README.md                       ← 你正在看的
├── LICENSE                         ← CC BY-NC-ND 4.0
├── _index.md                       ← 論文進度儀表板
├── 00_overall_review/              ← 論文總綱（自行建立）
│   └── README.md                   ← 總綱撰寫指引
├── ch1_introduction/               ← 第一章：緒論
│   ├── README.md                   ← 章節說明
│   ├── draft.md                    ← 初稿（自行撰寫/由 AI 輔助生成）
│   └── notes.md                    ← 討論筆記與待辦
├── ch2_literature/                 ← 第二章：文獻探討
│   ├── README.md                   ← 章節說明
│   ├── draft.md                    ← 初稿
│   └── notes.md                    ← 討論筆記
├── ch3_methodology/                ← 第三章：研究方法
│   ├── README.md                   ← 章節說明
│   ├── case_protocol.md            ← 個案研究協議書模板
│   ├── interview_consent.md        ← 訪談同意書模板（含受訪者八項權利）
│   ├── invitation_letter.md        ← 訪談邀請信模板
│   ├── thankyou_letter_template.md ← 訪談後感謝信模板
│   ├── transcript_confirmation_template.md ← 逐字稿確認信模板
│   └── operationalization.md       ← 操作化對齊表（CH2↔CH3 橋接，自行建立）
├── ch4_case_study/                 ← 第四章：個案分析
│   ├── README.md                   ← 章節說明
│   ├── interviews/
│   │   └── interview_template.md   ← 訪談記錄表模板（含 CIMO 編碼欄）
│   └── timeline_draft.md           ← 時間軸（自行建立）
├── ch5_conclusion/                 ← 第五章：結論
│   ├── README.md
│   └── draft.md
├── shared/                         ← 共享資源
│   ├── dba-thesis-manual.md        ← DBA 論文操作手冊（完整 CH1-CH5 流程）
│   ├── glossary.md                 ← 中英術語對照表
│   ├── references_master.bib       ← 全論文統一引用庫
│   ├── amj-writing-framework.md    ← AMJ 寫作框架（CH1-CH3 核心摘要）
│   └── prompt_templates/           ← AI 輔助寫作協定
│       ├── distill_paper.md        ← 文獻蒸餾協定
│       ├── cross_analysis.md       ← 縱橫分析協定
│       └── expand_section.md       ← 章節擴寫協定
└── references/                     ← 參考資源
    └── suggested_readings.md       ← 奠基文獻建議閱讀順序
```

## 使用方式

1. **複製整包**：`git clone` 或下載 ZIP
2. **填入你的個案**：將 `[個案公司]` `[產業別]` 等佔位符替換為你研究的主題
3. **建立總綱**：在 `00_overall_review/` 寫下你的研究問題與理論框架
4. **按手冊推進**：對照 `shared/dba-thesis-manual.md` 逐章執行

## 致謝（ATTRIBUTION）

本模板的設計思想借鑑以下資源：

- **Deep Research Agent (DRA)** by CYC2002tommy（MIT License）— 7-Phase 文獻檢索骨架概念啟發
- **AMJ Editor Articles**（Colquitt & George, 2011）— 寫作框架與審查標準
- **Yin (2018) Case Study Research** — 個案研究設計方法論

## 授權

本模板採用 CC BY-NC-ND 4.0。你可以：
- ✅ 自由複製、分享給同事/同學/訂戶
- ✅ 用於自己的論文研究（包含商業用途的學位論文）
- ❌ 不能修改後宣稱是自己的模板
- ❌ 不能包裝成付費產品販售

詳細條文請見 `LICENSE` 檔案。