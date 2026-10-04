# SONA — AI 協作 Handoff

## 1. 專案資訊

- 專案名稱：SONA — Today, in One Song.
- 原產品：Spotify
- 專案類型：RWD Web / App 重新設計
- AI 工具：Claude
- 設計工具：Figma
- Figma：［[Figma URL](https://www.figma.com/design/vtpn8FXGp3j4qGCu8Y9bef/RWD_%E5%8C%BF%E5%90%8D%E4%BB%A3%E7%A2%BC_%E5%B0%88%E6%A1%88%E5%90%8D?node-id=1-6&t=PULK53HOuZICqpKt-1)］
- GitHub：［GitHub URL］
- 最後更新：［2026-10-05］

---

## 2. AI 協作原則

本專案使用 AI 作為設計與整理的協作工具。

AI 可以協助：

- 整理問題與設計方向
- 提供設計方案
- 產生文字草稿
- 協助建立 Figma 介面
- 協助檢查設計與互動流程

最終的設計決定由本人判斷。

AI 產出的內容不直接視為最終答案，會依照課程要求、原產品問題、使用情境與實際介面結果進行確認與修改。

---

## 3. 專案背景

本專案以 Spotify 為重新設計對象。

主要問題：

1. 新音樂的偶然發現較少。
2. 以當下心情作為音樂探索起點的體驗較弱。
3. 較難從陌生使用者的選曲發現音樂。

重新設計後的概念為：

**SONA — Today, in One Song.**

核心方向是讓使用者：

- 從 Mood 開始探索音樂。
- 從其他使用者的 Today's Song 發現新音樂。
- 用一首歌分享當天的心情。
- 不需要撰寫文字型貼文。

---

## 4. AI 協作紀錄

> 以下紀錄依實際 AI 使用情況持續更新。
> 每次協作應記錄「任務、AI 輸出、本人判斷、修改原因」。


| # | 日期 | AI 工具 | 協作內容 | AI 產出 | 本人判斷／決定 |
|---|---|---|---|---|---|
| 01 | 2026-10-04 | ChatGPT | 整理 SONA 專案概念與原產品方向 | 整理 Spotify redesign 與 SONA 的關係 | 確定以 Spotify 為原產品，SONA 作為 redesign 後的設計方向 |
| 02 | 2026-10-04 | ChatGPT | 分析 Spotify 的產品問題 | 提出新音樂探索、Mood 探索、音樂分享等問題方向 | 選擇 3 個問題作為本次 redesign 的主要問題 |
| 03 | 2026-10-04 | ChatGPT | 整理 Problem Statement | 將問題整理為「在哪個畫面／發生什麼／影響誰／證據」的格式 | 確認三個 Problem 的內容與文字表達 |
| 04 | 2026-10-04 | ChatGPT | 建立 Persona | 提出主要 Persona 與次要 Persona 的基本資料、目標與痛點 | 確認 Persona 與 SONA 的目標使用者方向一致 |
| 05 | 2026-10-04 | ChatGPT | 整理使用情境與 Design Goals | 建立 3 個主要使用情境與 4 個設計目標 | 選擇與 SONA 核心功能直接相關的情境與目標 |
| 06 | 2026-10-04 | ChatGPT | 設定 Success Metrics | 提出 Mood、Today's Song、音樂探索等操作時間與成功條件 | 將可測量的條件作為後續測試依據 |
| 07 | 2026-10-04 | ChatGPT | 建立 Design Claims | 提出 3 個 Design Claims | 確認三個 Claim 分別對應三個主要問題，並保留取捨說明 |
| 08 | 2026-10-04 | ChatGPT | 整理 Visual Direction | 將「情緒、連結、安定」轉換成色、形、質、動與介面決定 | 確定只使用 3 個關鍵詞，並採用「關鍵詞 → 視覺手段」的方式 |
| 09 | 2026-10-05 | ChatGPT | 討論 CIS 色彩方向 | 提出黑、藍、紫為主要色彩，以及淡紫、水色、紫白等輔助色 | 確定以黑色作為主要背景，藍＋紫作為品牌核心色，並使用藍紫漸層 |
| 10 | 2026-10-05 | ChatGPT | 整理 CIS Color Palette | 建議 Brand / Background / Surface / Accent / Text 等色彩層級 | 確認主要色彩與介面狀態的使用方式 |
| 11 | 2026-10-05 | Claude | 根據 SONA 的專案方向與設計需求製作 UI 試作一 | 產生第一版 SONA UI 試作 | 將第一版作為後續設計比較與修改的參考 |
| 12 | 2026-10-05 | Figma AI | 根據 SONA 的設計方向製作第二版 UI 設計 | 產生第二版 SONA UI 設計 | 與第一版比較後，確認第二版的視覺與介面方向 |
---

## 5. AI 產出與本人判斷

### Problem Definition

AI 協助整理 Spotify 的問題，但部分原始描述過於絕對。

例如不能直接寫：

> 「Spotify 沒有 Mood 功能。」

因為 Spotify 本身已有 Mood 相關內容。

因此修改為：

> 「以當下心情作為音樂探索起點的體驗較弱。」

這樣可以更準確描述重新設計的問題。

---

### Social Sharing

AI 初步提出的方向可能容易讓人誤解為 Spotify 沒有社群分享功能。

實際上 Spotify 有歌曲分享功能，因此本專案將問題重新定義為：

> 「較難從陌生使用者的選曲發現音樂。」

重新設計並不是移除原有分享功能，而是增加新的社群探索方式。

---

### Visual Direction

AI 曾提出使用具體符號作為視覺概念，但本專案最後依照意象看板的「關鍵詞 → 視覺手段」方式處理。

最終關鍵詞：

- 情緒 Mood
- 連結 Connection
- 安定 Calm

再從關鍵詞延伸：

- 色
- 形
- 質
- 動
- 介面上的決定

---

## 6. Figma 協作流程

AI 協助製作 Figma 時，採用以下流程：

1. 先確定 Brief 與原產品問題。
2. 確定設計目標與 Design Claims。
3. 確定意象看板與視覺關鍵詞。
4. 確定 CIS、色彩與文字規範。
5. 再請 AI 協助建立 Figma 介面。
6. 檢查 AI 產出的結果是否符合原本的設計決定。
7. 若不符合，修改 AI 產出。
8. 將修改原因記錄於版本紀錄與 AI 協作紀錄。

---

## 7. 設計判斷

本專案的重要設計決定：

### 01｜Today's Song

將「今天正在聽的一首歌」作為社群內容單位。

原因：

降低分享門檻，並讓使用者可以從其他人的選曲發現歌曲。

---

### 02｜Mood Discovery

將 Mood 作為音樂探索入口。

原因：

使用者有時不知道想聽哪首歌，只知道自己現在想要的感覺。

---

### 03｜藍紫色視覺方向

使用藍色與紫色的漸層作為主要視覺方向。

原因：

希望同時表現情緒變化、使用者之間的連結，以及安定的音樂體驗。

---

## 8. 版本紀錄

### v1

主要完成：

- Problem Definition
- Design Brief
- Persona
- Design Goals
- Success Metrics
- Design Claims
- 意象看板初版

### v2

主要完成：

- CIS
- 色彩變數
- Text Styles
- Components
- 第一版 RWD 介面

### v3

主要完成：

- 依測試結果修改介面
- 修正互動流程
- 補充 RWD
- 更新 Design Claims 的驗證證據

### 繳交版

最終確認：

- 8 個 Figma 必要頁面
- M / T / D 三種寬度
- Prototype
- Design Claims
- 驗證證據
- GitHub 文件
- Pitch 與逐字稿

---

## 9. 重要連結

### Figma

［Figma URL］

### GitHub

［GitHub URL］

### AI 討論紀錄

［AI 討論串 URL］

### Pitch

［YouTube 不公開 URL］

---

## 10. 備註

本文件會隨專案進度更新。

AI 協作紀錄以實際發生的工作為準，不虛構尚未進行的測試、使用者回饋或設計結果。
