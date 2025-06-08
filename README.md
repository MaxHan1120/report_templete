# NTU LaTeX Report Template

本專案提供台大學生常用的 LaTeX 報告模板，支援分段撰寫、中文斷行與自訂格式，適用於課堂報告或期末作業。

## ✅ 如何使用本模板

### 1. 從 GitHub 複製模板

打開終端機或 PowerShell，執行以下指令（請將 `your-username` 改成你的 GitHub 使用者名稱）：

```bash
git clone https://github.com/your-username/ntu-latex-template.git MyReport
cd MyReport
```

### 2. 移除 Git 關聯（可選）

若你只是想使用模板，不需要保留原始 Git 記錄，可以移除 `.git`：

```bash
rm -rf .git
```

### 3. 開始撰寫報告

打開 `main.tex`，使用你慣用的 LaTeX 編輯器（如 VSCode + LaTeX Workshop、TeXstudio）開始編輯即可。

### 4. 編譯方式

建議使用 `xelatex` 編譯：

```bash
xelatex main.tex
```

若有子目錄與中文內容，建議編譯兩次確保目錄與換行正常。

---

## 📁 結構說明

```plaintext
ntu-latex-template/
├── main.tex              # 主檔案
├── BMEReport.cls         # 自訂 LaTeX 樣式檔
├── contents/             # 各章節內容（可拆成多檔）
├── fonts/                # 中文字體（可選）
├── images/               # 插圖資料夾
└── .gitignore
```

---

## 📝 注意事項

* 建議使用支援 UTF-8 編碼與中文斷行的編譯方式（如 XeLaTeX）。
* 若換行出現 CRLF/LF 警告，可忽略，或設定 Git 換行處理方式。
