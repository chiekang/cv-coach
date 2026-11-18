<p align="center"><b>輔仁大學 Fu Jen Catholic University</b><br><sub>Financial Market and Global Business · FMGB<br>By Francis Lee</sub></p>

# 📄 CV Coach 履歷教練 `FMGB`

**線上使用 Use it online:** https://chiekang.github.io/cv-coach/

為輔仁大學「Financial Market and Global Business」全英課設計的一頁履歷工具。
A one-page CV builder for the English-taught course *Financial Market and Global Business* at Fu Jen Catholic University.

學生用中文或英文回答幾個問題，就能做出一份一頁、乾淨、ATS 友善的履歷；右邊會即時顯示預覽，以及依照課堂五個標準估算的分數。
Students answer a few short questions in Chinese or English and get a clean, one-page, ATS-friendly CV, with a live preview and an estimated score on the five criteria taught in class.

---

## 五個評分標準 The five criteria

| 標準 Criterion | 重點 What it checks |
|---|---|
| **Easy to read** 易讀 | 單欄、一頁、每點一行、不用彩色模板 One column, one page, one line per bullet, no coloured template |
| **Right content** 內容正確 | 姓名、email、電話、城市、目標職位、畢業年月、經歷、技能，沒有 `[Month, Year]` 之類的空白佔位 Complete details and a target job; no unfilled placeholders |
| **Proof** 有證據 | 每項技能都有程度和證據 Every skill has a level and proof |
| **Strong words** 強動詞 | 以 Organized、Analyzed 等動詞開頭，避免 Handled、Assisted with、Responsible for Start with strong verbs |
| **Results** 有成果 | 用真實的數字呈現成果 Show results with real numbers |

預估分數 = 50 + 五項總分 ÷ 2。這是用規則估算的參考值，不是老師的正式成績。
Estimated score = 50 + (sum of the five scores) ÷ 2. It is a guide, not the teacher's grade.

---

## 功能 Features

- **兩種開始方式 Two ways to start**：從頭開始，或上傳舊履歷（PDF、Word、照片、貼上文字），先診斷、再改進。 Start from scratch, or upload an old CV to get a diagnosis first.
- **四種語言組合 Four language modes**：中→英、英→英、英→中、中→中。 ZH→EN, EN→EN, EN→ZH, ZH→ZH.
- **AI 協作＋教練 AI as collaborator and coach**：每一句給出可用的改寫，並用中英文一行說明為什麼這樣改。缺數字時 AI 會問學生，**不會編造**。 Each line gets a ready-to-use rewrite plus a one-line bilingual explanation. If a number is missing, the AI asks; it never invents facts.
- **五項燈號與預估分數 Five lights and an estimated score**，上傳舊履歷時會顯示「改前 → 改後」。 Before → after score when you upload an old CV.
- **輸出 Export**：一頁 A4 PDF、純文字複製、存檔後可再載入。 One-page A4 PDF, plain text, and a save file you can reopen.
- **範例 Examples**：內建「好範例」和「待改範例」（虛構人物），可作課堂活動。 A strong and a weak example (fictional people) for class activities.

---

## 怎麼使用 How to use

1. 打開上面的網址。 Open the link above.
2. 選擇填寫語言和履歷語言。 Choose the input and output languages.
3. 選「從頭開始」或「上傳舊履歷」。 Start from scratch or upload an old CV.
4. 一步一步填寫，按「AI 幫我改寫」。 Fill in each step and press "Improve".
5. 完成匯出頁勾選「每一句都是真的」，下載 PDF。 On the Finish page, confirm everything is true and download the PDF.

### 用你自己的 AI Use your own AI

不需要 Claude 帳號。在「AI 來源」選「我自己的 AI」：
No Claude account needed. Choose "My own AI" under *Which AI?*:

1. 按任何 AI 按鈕，**複製提示詞**。 Press any AI button and copy the prompt.
2. 貼到 Gemini、ChatGPT 或 Claude，送出。 Paste it into Gemini, ChatGPT or Claude.
3. 把 AI 的回答**整段貼回**頁面，按「套用」。 Paste the whole answer back and press Apply.

如果頁面說「讀不到 JSON」，請告訴 AI「只回覆 JSON」再貼一次。
If the page says it cannot read the answer, ask your AI to "reply with only the JSON" and paste again.

上傳照片時，請在你自己的 AI 裡附上履歷照片，再貼上提示詞。
When uploading photos, attach the photos in your own AI chat before pasting the prompt.

---

## 隱私與誠信 Privacy and honesty

- 所有資料只存在你自己的瀏覽器，這個網站沒有伺服器，不會收集或上傳任何內容。 Everything stays in your browser. There is no server and nothing is collected.
- 上傳 PDF、Word 或貼上的文字時，電話和 email 會先在瀏覽器裡遮掉，再給 AI。照片會整張交給你選的 AI。 For PDF, Word and pasted text, phone numbers and emails are masked in your browser before anything goes to an AI. Photos are sent as they are.
- 請不要放身分證字號、護照號碼或完整住址。 Do not include ID numbers, passport numbers or home addresses.
- AI 只是幫手。匯出前請確認**每一句都是真的、每個數字都是你自己的**。 The AI is a helper: make sure every line is true and every number is yours.

---

## 給老師 For the teacher

- 這是單一檔案 `index.html`，沒有後端、沒有資料庫、沒有金鑰，不會產生費用。 It is a single static file: no backend, no database, no API keys, no cost.
- AI 提示詞和評分規則都寫在 `index.html` 裡（搜尋 `RULES`、`PARSE`、`score(`），可以直接修改。 The AI prompts and the scoring rules live in `index.html` (search for `RULES`, `PARSE` and `score(`).
- 學生可以把「存檔 (.json)」傳給你，你在頁面按「載入存檔」就能看到他的內容和分數。 Students can send you their saved `.json`; open it with "Open saved file" to see their work and score.
- 評分是規則估算，會與人工批改有落差：它的目的是讓學生知道往哪裡改。 The score is rule-based and will differ from hand grading; its job is to show students what to improve.

## 部署 Deployment

GitHub Pages：Settings → Pages → Deploy from a branch → `main` / `(root)`。
更新時直接覆蓋 `index.html` 並 commit，網址不變。
To update, replace `index.html` and commit; the URL stays the same.

## 已知限制 Known limits

- 照片和掃描檔要靠 AI 辨識，辨識後請學生核對內容有沒有讀錯或漏掉。 Photos and scans are read by AI: students must check what was read.
- 英文 PDF 是文字格式（ATS 可讀）；中文 PDF 目前是圖片格式。 English PDFs are real text (ATS-readable); Chinese PDFs are images for now.
- 評分燈號是規則檢查，無法判斷句子是否真實、是否適合該職位。 The lights cannot judge whether a line is true or fits the job.

---

課程 Course: Financial Market and Global Business · 輔仁大學 Fu Jen Catholic University
By Francis Lee
