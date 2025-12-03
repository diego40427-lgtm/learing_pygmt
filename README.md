# 🗺️ PyGMT 地理繪圖入門：繪製第一張世界地圖

![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=flat-square&logo=python)
![PyGMT](https://img.shields.io/badge/PyGMT-v0.12.0%2B-orange?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

歡迎來到 PyGMT 學習專案！
本專案旨在展示如何使用 **PyGMT** (Python interface for the Generic Mapping Tools) 來繪製高品質的地理空間圖表。PyGMT 結合了 Python 的易用性與 GMT 的強大繪圖能力，非常適合地球科學與地理資訊領域的應用。

---

## 📖 目錄 (Table of Contents)

- [專案簡介](#-專案簡介)
- [成果預覽](#-成果預覽)
- [環境安裝](#-環境安裝)
- [完整程式碼](#-完整程式碼)
- [參數詳解](#-參數詳解)

---

## 🚀 專案簡介

本教學範例將帶領您完成以下目標：
1.  初始化 PyGMT 畫布。
2.  設定地圖投影法 (Mollweide Projection)。
3.  繪製海岸線並填入陸地與海洋顏色。
4.  輸出高解析度的 PNG 圖片。

---

## 🖼️ 成果預覽

執行程式碼後，您將獲得如下的全球地圖：

![PyGMT 世界地圖範例](pygmt_first_map.png)

> **注意**：若上方圖片未顯示，請確保您已執行程式碼並將生成的 `pygmt_first_map.png` 上傳至 GitHub Repository 根目錄。

---

## ⚙️ 環境安裝

在開始之前，請確保您的環境已安裝 PyGMT。推薦使用 `conda` 進行安裝以確保 GMT 依賴庫正確配置。

```bash
# 方法一：使用 Conda (推薦)
conda install --channel conda-forge pygmt

# 方法二：使用 Pip (需預先安裝 GMT C library)
pip install pygmt
