# CandlePatternsZh

**CandlePatternsZh** aims to translate All Patterns indicators in TradingView into Chinese, combining educational content with TradingView's PineScript code tool to help traders better understand and apply technical analysis.

## 專案介紹 (Project Overview)
**CandlePatternsZh** 旨在將TradingView裡的All Patterns指標翻譯成中文，結合教育內容和TradingView的PineScript程式碼工具，幫助交易者更好地理解和應用技術分析。

- **中文化**：提供K線形態的中文名稱、解釋和交易策略。
- **PineScript工具**：自動檢測並視覺化K線形態，支援TradingView平台。
- **教育資源**：詳細的形態說明、圖表範例和中英對照表。

## 功能 (Features)
- Localized candlestick patterns with Chinese translations.
- PineScript scripts for detecting and visualizing patterns on TradingView.
- Educational guides with examples and trading strategies.

## 目前支援的K線形態 (Supported Patterns)
| 英文名稱 (English)       | 中文名稱 (Chinese) | 說明 (Description)                          |
|--------------------------|--------------------|---------------------------------------------|
| Doji                    | 十字星            | 開盤價與收盤價接近，反映市場猶豫。         |
| Hammer                  | 錘形線           | 長下影線，短實體，可能預示底部反轉。       |
| Bullish Engulfing       | 看漲吞沒         | 大陽線吞沒前一根陰線，表明買方力量增強。   |
| Bearish Engulfing       | 看跌吞沒         | 大陰線吞沒前一根陽線，表明賣方力量增強。   |

更多形態請參閱 [docs/](docs/)。

## 快速開始 (Getting Started)
1. 複製專案：
   ```bash
   git clone https://github.com/AsiaOstrich/CandlePatternsZh.git
   ```
2. 瀏覽 `docs/` 資料夾，查看K線形態的教育內容。
3. 將 `scripts/` 資料夾中的PineScript程式碼複製到TradingView的Pine Editor以應用。

## 專案結構 (Project Structure)
```
CandlePatternsZh/
├── docs/                   # 教育內容 (Educational content)
├── scripts/                # PineScript程式碼 (PineScript scripts)
├── examples/               # 圖表範例 (Chart examples)
├── translations/           # 中英對照翻譯 (Translations)
├── README.md               # 專案介紹 (Project overview)
├── CONTRIBUTING.md         # 貢獻指南 (Contribution guidelines)
├── LICENSE                 # MPL 2.0許可證 (MPL 2.0 License)
└── .gitignore              # Git忽略檔案 (Git ignore file)
```

## 貢獻 (Contributing)
歡迎參與貢獻！請閱讀 [CONTRIBUTING.md](CONTRIBUTING.md) 了解如何提交翻譯、程式碼或範例。

## 許可證 (License)
This project is licensed under the Mozilla Public License 2.0 - see the [LICENSE](LICENSE) file for details.

## 聯繫 (Contact)
有任何問題或建議？請在GitHub上開啟 [Issue](https://github.com/AsiaOstrich/CandlePatternsZh/issues) 或聯繫我們！