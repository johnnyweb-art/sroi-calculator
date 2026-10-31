# SROI 社會投資報酬率計算器

依據 Social Value International 八大原則（2012 建立，2014、2021 更新）與 Nicholls et al. (2012)《A Guide to Social Return on Investment》（2nd ed.）設計的單頁計算器。

## 功能

- 模式 A：評估性 SROI 計算，每位利害關係人可分別設定成果類型、調整因子與效益年期
- 模式 B：預測性 SROI 規劃（需 API Key）
- 負向成果扣除、主計算／情境分析分流、本地敏感性分析
- 教學範例：山林水 × 春燕生態農場（保守版，SROI 0.51:1）

## 部署

靜態網站，由 Netlify 從 `main` 分支自動部署，發布目錄為根目錄。

## 安全

**切勿將 Anthropic API Key 寫入任何檔案。** 請在網頁右上角輸入，Key 只存在使用者自己的瀏覽器 localStorage。
