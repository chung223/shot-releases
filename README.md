<img src="icon.png" width="128" alt="Shot 圖示">

# Shot

macOS 選單列截圖工具。這個 repo 放的是簽章並經 Apple 公證的安裝檔與自動更新資訊，原始碼不公開。

[English](#english)

## 下載與安裝

1. 到 [Releases](https://github.com/chung223/shot-releases/releases/latest) 下載最新的 `Shot-<版本>.dmg`。
2. 打開 DMG，把 Shot 拖進「應用程式」。
3. 打開 Shot。第一次會出現歡迎視窗，帶你開啟「螢幕錄製」權限（截圖一定要有）。

需要 macOS 26 以上，Apple 晶片與 Intel 的 Mac 都可以。Shot 住在選單列，沒有 Dock 圖示。

## 功能

- **截圖**：區域、視窗、全螢幕、上次的區域；捲動截圖自動拼成長圖。
- **截圖之後**：截圖掛在螢幕頂端的曬衣繩（或角落卡片）上，可以拷貝、拖進其他 App、釘在螢幕最上層。
- **標註**：箭頭、文字、形狀、螢光筆、步驟編號、尺規、從圖上取色、自動遮蔽 email 與金鑰等敏感資訊、背景美化。
- **錄影與 GIF**：可以顯示按鍵、高亮游標、在角落放鏡頭畫面；內建剪輯器修剪頭尾、去掉聲音、轉 GIF。
- **文字**：辨識截圖裡的文字與 QR code，或直接翻譯截圖。
- **截圖歷史**：用畫面裡的字搜尋以前的截圖，Apple Intelligence 自動取標題。
- **其他**：取色與量測、捷徑 App 與 Spotlight 動作、上傳到自己的 Cloudflare R2。

介面有繁體中文與英文，跟著系統語言切換。

## 更新

Shot 會自動檢查新版本，有新版時會提醒你，按一下就下載安裝。也可以從選單列的「檢查更新…」手動檢查。

## 隱私

- 截圖、文字辨識、翻譯、AI 命名都在你的 Mac 上處理，不會上傳。
- 沒有使用統計，也沒有追蹤。
- 只有兩種情況會連上網路：檢查更新（連到這個 GitHub repo），以及你自己設定 Cloudflare R2 之後的上傳。

## 回報問題

到 [Issues](https://github.com/chung223/shot-releases/issues) 開一則，附上 macOS 版本與 Shot 版本（設定 › 一般 最下面）。

---

## English

Shot is a menu bar screenshot tool for macOS. This repository hosts signed, Apple-notarized builds and update information; the source code is not public.

**Install:** download the latest `Shot-<version>.dmg` from [Releases](https://github.com/chung223/shot-releases/releases/latest), open it and drag Shot into Applications. Requires macOS 26 or later, on Apple silicon or Intel. On first launch, a welcome window helps you allow Screen Recording, which screenshots require.

**Features:** area, window and fullscreen screenshots and scrolling capture; a clothesline (or corner cards) for recent screenshots that you can copy, drag or pin; annotation with arrows, text, shapes, highlighter, counters, rulers, color picking, automatic redaction and backgrounds; screen recording and GIFs with keystrokes, cursor highlight and camera, plus a built-in trimmer; text and QR code recognition and screenshot translation; searchable screenshot history with Apple Intelligence titles; color picking and measuring; Shortcuts and Spotlight actions; uploads to your own Cloudflare R2. The interface is available in English and Traditional Chinese.

**Updates:** Shot checks for updates automatically, or choose Check for Updates… from the menu bar.

**Privacy:** screenshots, text recognition, translation and AI naming all run on your Mac. There are no analytics or tracking. Shot only goes online to check for updates (this GitHub repository) and to upload to Cloudflare R2 if you set that up.

**Feedback:** open an [issue](https://github.com/chung223/shot-releases/issues) with your macOS and Shot versions (shown at the bottom of Settings › General).
