# 🧠 Quick Note Sudoku

一款支援筆記模式的數獨遊戲，支援多平台，目標發行至：
- 🖥️ Windows / macOS（Steam）
- 📱 Android（Google Play）
- 📱 iOS（App Store）

本專案使用 [Tauri](https://tauri.app/) 建構桌面與行動應用，前端為 Vanilla JavaScript 製作。

## 🚀 功能簡介

- 9x9 數獨盤面
- 筆記模式
- 計時器與錯誤計數
- 響應式 UI 適應不同螢幕
- 準備支援 Web / 桌面 / 手機跨平台

## 📦 安裝與開發

### 1. 安裝依賴

```bash
npm install
```

### 2. 執行桌面開發版本（需安裝 Rust）

```bash
npm run tauri dev
```

### 3. 編譯發行版

```bash
npm run tauri build
```

### 4. Android 開發版本（需安裝 Android SDK / NDK）

```bash
npm run tauri android dev
```

### 5. macOS 或 iOS 開發（請至 macOS 環境操作）

> 請使用 macOS 並安裝 Xcode 以及 CocoaPods

```bash
npm run tauri ios dev
```

## 📁 專案結構

```
quick-note-sudoku/
├── src/                   # 前端 JS 程式碼
├── src-tauri/             # Rust + Tauri 設定與後端
├── package.json
├── tauri.conf.json
└── README.md              # ← 就是這份說明檔
```

## 📜 授權

本專案使用 MIT 授權。歡迎自由使用與修改！

---

如果你喜歡這個專案，歡迎 star ⭐ 或分享給朋友 😊
