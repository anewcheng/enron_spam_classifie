# 📧 Enron 電子郵件垃圾郵件分類器 (Enron Spam Classifier)

## 專案簡介

此專案旨在使用經典的 **Enron-Spam Dataset** 建立一個基於機器學習的二元分類模型，用於自動識別和過濾電子郵件中的垃圾郵件（Spam）和正常郵件（Ham）。

本專案採用 **Multinomial Naive Bayes (多項式樸素貝葉斯)** 模型，結合 **TF-IDF (Term Frequency-Inverse Document Frequency)** 技術進行文本特徵工程。

## 資料集 (Dataset)

* **名稱:** Enron-Spam Dataset (預處理版本)
* **來源:** 該資料集源自 Enron 電子郵件語料庫中已標註的垃圾郵件和正常郵件集合。
* **檔案:** 假設您已將資料整理為 `data/enron_spam_preprocessed.csv`，包含 `content` (郵件內容) 和 `label` (0=Ham, 1=Spam)。
* **任務:** 二元分類 (Binary Classification)。

## 運行環境要求 (Requirements)

您需要安裝 Python 3.x 及以下函式庫。

```bash
pip install -r requirements.txt
