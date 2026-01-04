# 雙月筆記 Bimonthly Notes

[English](#english) | 中文

一個輕量級的單一 HTML 檔案月曆應用程式，同時顯示兩個月份並支援筆記功能。

## 功能特色

- **雙月顯示**：垂直排列顯示本月與下月月曆
- **筆記功能**：內建文字編輯器，自動儲存
- **國定假日**：支援匯入自訂假日資料（含台灣假日範例）
- **本地儲存**：所有資料儲存在瀏覽器 LocalStorage
- **單一檔案**：無需安裝，開啟即用
- **響應式設計**：適應不同螢幕尺寸

## 快速開始

1. 下載 `index.html`
2. 用瀏覽器開啟
3. 開始使用！

## 假日資料格式

假日資料使用 JSON 格式，範例如下：

```json
{
  "holidays": [
    {"date": "2026-01-01", "name": "元旦"},
    {"date": "2026-02-14", "name": "春節"}
  ]
}
```

專案包含 `holidays-2026.json` 作為台灣 2026 年假日範例。

## 使用說明

### 匯入假日
1. 點擊「月曆」標題旁的 ⋯ 圖示
2. 選擇「匯入假日」
3. 上傳 JSON 檔案

### 筆記管理
- 筆記會在輸入 500ms 後自動儲存
- 點擊「筆記」標題旁的 ⋯ 圖示可匯入/匯出筆記

## 授權

MIT License

---

<a name="english"></a>

# Bimonthly Notes

A lightweight single-file calendar app displaying two months at once with integrated note-taking.

## Features

- **Dual-month View**: Display current and next month vertically
- **Note-taking**: Built-in text editor with auto-save
- **Holiday Support**: Import custom holiday data (includes Taiwan holidays example)
- **Local Storage**: All data stored in browser LocalStorage
- **Single File**: No installation required, just open and use
- **Responsive Design**: Adapts to different screen sizes

## Quick Start

1. Download `index.html`
2. Open with your browser
3. Start using!

## Holiday Data Format

Holiday data uses JSON format:

```json
{
  "holidays": [
    {"date": "2026-01-01", "name": "New Year"},
    {"date": "2026-02-14", "name": "Spring Festival"}
  ]
}
```

The project includes `holidays-2026.json` as an example for Taiwan 2026 holidays.

## Usage

### Import Holidays
1. Click the ⋯ icon next to "Calendar" title
2. Select "Import Holidays"
3. Upload JSON file

### Note Management
- Notes auto-save 500ms after typing
- Click the ⋯ icon next to "Notes" title to import/export notes

## License

MIT License

