#多媒體播放器（Media Player）

##專案簡介
本專案使用 C# Windows Forms 開發，製作一個多媒體播放器。
使用者可以透過瀏覽功能選擇影片或音樂檔案，並進行播放、暫停與停止等操作。

本系統整合 Windows Media Player COM 元件、OpenFileDialog 與 Windows Forms 圖形介面，提供簡易的影音播放功能與良好的操作體驗。

---

##功能說明

###瀏覽媒體檔案
使用 OpenFileDialog 選擇影音檔案。

支援格式：

* `.wmv`
* `.mp4`
* `.avi`

---

###主畫面
<img width="2376" height="1663" alt="image" src="https://github.com/user-attachments/assets/4f2b3e17-b100-4aa1-8afe-3eff9aad9fd0" />

###瀏覽影片
<img width="2345" height="1666" alt="image" src="https://github.com/user-attachments/assets/06f02d7e-cf7e-4803-9411-40f1f5183678" />

###播放影片
<img width="2371" height="1655" alt="image" src="https://github.com/user-attachments/assets/dba8f8bc-30cf-4c97-bec8-b45fcddbb019" />

###暫停播放
<img width="2369" height="1708" alt="image" src="https://github.com/user-attachments/assets/179eeb3e-9b38-4f9c-b05f-fe3c03447155" />

###停止播放
<img width="2365" height="1685" alt="image" src="https://github.com/user-attachments/assets/41943a6a-77f2-4658-8b9c-d0d4c0022b04" />


---

##執行說明

###開發環境

* Visual Studio 2022
* .NET Framework（Windows Forms）

---

###執行步驟

1. 開啟專案（MediaPlayer.sln）
2. 點擊「開始（Start）」執行程式
3. 點擊【瀏覽】選擇影片檔案
4. 點擊【播放】開始播放影片
5. 可使用【暫停】與【停止】控制影片播放

---


##使用技術

* C#
* Windows Forms
* Windows Media Player COM 元件
* OpenFileDialog
* AxWindowsMediaPlayer
* 事件驅動（Click Event）

---

##專案架構

```text
MediaPlayer
│
├── Form1.cs
├── Form1.Designer.cs
├── Program.cs
├── MediaPlayer.sln
├── README.md
└── References
    ├── AxInterop.WMPLib.dll
    └── Interop.WMPLib.dll
```

---

##開發紀錄（Commit History）

本專案透過 GitHub 進行版本控制，
提交紀錄清楚記錄以下開發過程：

* 建立 Windows Forms 多媒體播放器介面
* 加入 Windows Media Player COM 元件
* 完成影片播放功能
* 新增暫停與停止播放功能
* 加入 OpenFileDialog 檔案瀏覽功能
* 支援 MP4、WMV、AVI 格式播放
* 美化播放器介面配置
* 調整按鈕位置與影片顯示區域
* 撰寫 README 與執行畫面說明

---

##備註

* 使用 Windows Media Player COM 元件播放影音
* uiMode 已設定為 `none`
* 播放控制由自訂按鈕操作
* 已移除 bin / obj / .vs 資料夾後再上傳 GitHub

---

##心得
透過本專案學習到：

* Windows Forms UI 設計
* COM 元件使用方式
* Windows Media Player 控制方法
* OpenFileDialog 檔案選擇功能
* 多媒體播放控制邏輯
* GitHub 版本控制流程

提升了影音播放程式的實作能力與介面設計技巧。
