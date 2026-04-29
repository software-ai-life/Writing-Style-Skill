# Writing-Style-Skill

A writing style skill that helps AI generate technical articles in my tone, structure, and teaching style.

## 專案介紹

`Writing-Style-Skill` 是一個根據我的文章樣本整理出的寫作風格 skill repository。

這個專案的目標很簡單：

- 讓 AI 更準確模仿我的寫作風格
- 讓技術文章不只正確，還要有我的語氣與節奏
- 把零散的寫作習慣整理成可重複使用的規則

這份 skill 特別適合拿來生成：

- 技術教學文章
- 工具介紹文
- 論文閱讀筆記
- 資料分析與 Python 相關內容
- 教學型、條理清楚、對新手友善的技術內容

---

## 這個 repo 在做什麼？

這個 repo 主要做兩件事：

1. 蒐集我的寫作樣本
2. 從樣本中萃取可供 AI 使用的寫作規則

也就是說，這不是單純放文章的資料夾，而是一個把「我的寫作方式」轉成 AI 可理解格式的專案。

---

## 專案內容

### 1. `SKLL.md`

這是核心文件，整理了我的：

- 語氣
- 結構偏好
- 教學節奏
- 常見句型
- 適合的文章類型
- 應避免的寫法

AI 在生成內容時，可以優先讀取這份檔案，來對齊寫作風格。

### 2. `example/`

這裡放的是實際寫作樣本，用來提供風格依據。

這些文章會幫助 AI 理解：

- 我如何開頭
- 我如何拆解概念
- 我如何做條列整理
- 我如何用比較親切的方式解釋技術內容
- 我如何收尾與做小結

---

## 專案結構

```text
Writing-Style-Skill/
├─ SKLL.md
├─ README.md
└─ example/
   ├─ page-X.md
   ├─ page-X.md
   ├─ page-X.md
   └─ page-X.md
```

---

## 寫作風格特色

這份 skill 所定義的寫作風格，大致有以下特徵：

- **技術導向，但不生硬**
- **像朋友在教你，而不是像文件在命令你**
- **重視背景、動機與脈絡**
- **習慣把複雜內容拆成清楚的小段落**
- **喜歡用條列、編號與小標整理資訊**
- **常見節奏是：先講為什麼，再講怎麼做，最後做重點總結**
- **偏向新手也能順順讀懂的教學型文章**

---

## 適用情境

你可以把這個 repo 用在：

- 建立個人寫作風格 prompt
- 訓練 AI 協助寫部落格文章
- 讓 AI 幫忙延續既有文章口吻
- 建立 personal content generation workflow
- 作為其他 writing agent / content agent 的 style layer

---

## 使用方式

### 方法一：把 `SKLL.md` 當成 system / style prompt

在讓 AI 寫文章前，先提供 `SKLL.md`，再補上你的主題需求，例如：

- 想寫的主題
- 目標讀者
- 文章類型
- 是否需要程式碼範例
- 是否要加入比較、優缺點或小結

### 方法二：搭配 `example/` 一起使用

如果你希望 AI 更像你的實際文風，可以同時提供：

- `SKLL.md`
- `example/` 中的 1 到 3 篇代表文章

這樣通常會比只給 prompt 更穩定。

### 方法三：作為寫作工作流的一部分

你也可以把這個 repo 接到：

- AI agent workflow
- content generation pipeline
- RAG / personal knowledge base
- 自動化文章草稿生成流程

---

## 推薦工作流程

1. 先挑選幾篇最能代表自己風格的文章放進 `example/`
2. 根據樣本整理出 `SKLL.md`
3. 讓 AI 先讀 `SKLL.md`
4. 再給文章主題與需求
5. 請 AI 產出初稿
6. 持續根據輸出結果微調 `SKLL.md`

這樣這份 skill 就會越來越像你，而不是只是一份靜態說明文件。

---

## 這個 repo 適合誰？

這個 repo 特別適合：

- 想建立個人寫作風格資產的人
- 會持續寫技術文章的人
- 想讓 AI 幫忙寫稿，但又不想失去個人風格的人
- 想把自己的知識輸出流程標準化的人