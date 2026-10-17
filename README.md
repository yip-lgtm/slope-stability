# Slope Stability

靜態網頁版邊坡穩定分析示範。

**線上預覽**：https://yip-lgtm.github.io/slope-stability/

## 功能

- 點擊畫布定義坡面
- 輸入 \(c'\)、\(\phi'\)、單位重、地下水位
- 動態規劃搜尋非圓弧臨界滑動面
- 簡易 Janbu 法計算安全係數（含 \(f_0\) 修正）

## 方法說明

| 方法 | 本頁 | 建議工具 |
|---|---|---|
| Simplified Janbu | 有實作 | 本頁（快速檢查） |
| Bishop Simplified | — | [pySlope](https://github.com/JesseBonanno/PySlope) |
| Spencer | — | [OGR-Slip2D](https://github.com/samuelsl27/OGR-Slip2D) |
| Morgenstern-Price | — | [OGR-Slip2D](https://github.com/samuelsl27/OGR-Slip2D) |

OGR-Slip2D 驗證誤差（相對參考案例）：Spencer ≈ +0.64%，Morgenstern-Price ≈ +0.53%。

## 使用

1. 將本資料夾推到 GitHub 倉庫 `slope-stability`
2. 開啟 GitHub Pages（來源：main 分支 `/` 或 `/docs`）
3. 開啟 https://yip-lgtm.github.io/slope-stability/

## 限制

本頁僅供快速檢查與教學。正式工程報告請使用 Slope/W（Morgenstern-Price）或 OGR-Slip2D。

介面參考：[SSA 邊坡穩定分析](https://cychen59.github.io/ssa-slope-stability/)
