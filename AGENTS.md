# AGENTS.md

## 規定
- 所有的回應都使用繁體中文。
- 專案所使用的程式語言為 Python。
- 使用 conda 管理 Python 套件。
- Conda 的環境是 `iem_python`（已驗證：Python 3.12.13）。

## 執行與現狀
- conda 預設不在 PATH 上，執行請用完整路徑，例如：
  `C:\Users\user\anaconda3\Scripts\conda.exe run -n iem_python python --version`
- Greenfield repo — 目前僅有 `README.md`（計算機程式）、Python `.gitignore` 與本檔，尚無原始碼、依賴清單（`environment.yml` / `requirements*.txt` / `pyproject.toml` 皆無）、測試或 CI。
- 尚無已驗證的執行 / 測試 / lint 指令，不可臆測；新增設定後請在此記錄指令。
