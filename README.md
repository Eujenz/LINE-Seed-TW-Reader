# LINE Seed TC Reader｜台灣在地化簡轉繁閱讀字體

![Typeface Preview](https://img.shields.io/badge/Font-LINE_Seed-00C300?style=for-the-badge&logo=line)
![License](https://img.shields.io/badge/License-OFL_1.1-blue.svg?style=for-the-badge)
![Category](https://img.shields.io/badge/Category-E--Reader-orange?style=for-the-badge)

這是一款專為 **電子閱讀器 (Kindle, Kobo, mooInk)** 打造的簡轉繁字體。基於 LINE 官方推出的 [LINE Seed](https://seed.line.me/) 字體進行改製，透過字形對映技術，讓您在閱讀簡體書籍時，能自動呈現為精美的**台灣繁體字形與在地化用語**。

## ✨ 專案特點

- **🇹🇼 台灣用語在地化**：不僅是字形轉換，更整合了 OpenCC 台灣辭彙修正（如：軟件→軟體、質量→品質、屏幕→螢幕），提供最純粹的台灣閱讀體驗。
- **📖 閱讀器優化**：針對 E-ink 螢幕特性調整，確保在不同解析度下皆能保持清晰的對比度。
- **🎨 多重字重選擇**：提供從纖細到極粗共四種字重，滿足從詩歌內文到章節標題的所有需求。
- **🛠️ 開源技術基礎**：使用 [TCFontCreator](https://github.com/GuiWonder/TCFontCreator) 腳本進行精準的字形映射處理。

---

## 📦 字體規格與檔名對照

本專案包含以下四種字重檔案：

| 檔案名稱 | 字重類型 | 建議用途 |
| :--- | :--- | :--- |
| `LINESeedTW_TTF_Th.ttf` | **Thin** | 詩集、細膩排版、高解析度設備 |
| `LINESeedTW_TTF_Rg.ttf` | **Regular** | **[推薦]** 標準內文閱讀，長時間不疲勞 |
| `LINESeedTW_TTF_Bd.ttf` | **Bold** | 強調段落、章節標題、強光環境閱讀 |
| `LINESeedTW_TTF_Eb.ttf` | **ExtraBold** | 書名、極粗標題、封面設計 |

---

## 🚀 安裝指南

### 對於 Kindle 使用者
1. 將 Kindle 連接至電腦。
2. 將 `.ttf` 檔案複製到 Kindle 根目錄下的 `fonts` 資料夾中。
3. 在書籍閱讀介面點擊 `Aa` 選單 -> `字體` -> 選擇 `LINE Seed TW TC`。

### 對於 Kobo 使用者
1. 將 Kobo 連接至電腦。
2. 在 Kobo 根目錄建立一個名為 `fonts` 的資料夾（若已存在則忽略）。
3. 將 `.ttf` 檔案放入該資料夾。
4. 重新啟動閱讀器後即可在設定中選擇。

---

## 🛠️ 製作資訊與工具

- **底層字體**：[LINE Seed JP/KR](https://seed.line.me/)
- **轉換工具**：[TCFontCreator](https://github.com/GuiWonder/TCFontCreator)
- **詞庫來源**：OpenCC 台灣慣用語轉換辭典 (`s2twp.json`)

---

## ⚖️ 授權與版權聲明 (Legal Information)

1. **原始字體版權**：LINE Seed 字體之智慧財產權歸 **LINE Corporation** 所有。
2. **本專案授權**：本修改版字體依據 [SIL Open Font License 1.1](http://scripts.sil.org/OFL) 協議釋出。
3. **使用限制**：
    - 您可以自由使用、研究、修改及分發本字體。
    - **不得單獨販售字體檔案。**
    - 修改版字體必須同樣以 SIL OFL 1.1 協議釋出。
4. **免責聲明**：本專案僅供學術研究與個人閱讀交流使用，請勿用於任何違反法律之用途。

---

## 🙏 致謝
感謝 **LINE Corporation** 提供優質的開源字體，以及 **GuiWonder** 開發的 `TCFontCreator` 工具，讓台灣讀者能有更好的閱讀選擇。
