# DQN Homework 3

本專案為深度學習課程 Homework 3，主題為 DQN 及其變體在 Gridworld 環境中的實作與比較。

## 作業內容

- HW3-1: 比較 Naive DQN 與 Replay Buffer DQN（static mode）
- HW3-2: 比較 Vanilla DQN、Double DQN、Dueling DQN（player mode）
- HW3-3: 使用 PyTorch Lightning 改寫 DQN 訓練流程（random mode），並加入訓練技巧

## 專案檔案

- HW3.ipynb: 作業主程式（含三題實作與結果視覺化）
- Gridworld.py: Gridworld 環境邏輯
- GridBoard.py: Grid board 結構與狀態表示
- report.txt: 作業報告（中文正式版）
- 對話紀錄.txt: 與助理互動紀錄

## 環境需求

- Python 3.10+（建議使用虛擬環境）
- numpy
- matplotlib
- torch
- pytorch-lightning
- jupyter

## 安裝套件

```bash
pip install numpy matplotlib torch pytorch-lightning jupyter
```

## 執行方式

1. 開啟 HW3.ipynb。
2. 由上到下依序執行所有 cells。
3. 觀察三題比較結果與訓練曲線。

## 備註

- Notebook 內已包含固定 random seed 設定，方便重現結果。
- random mode（HW3-3）表現對超參數敏感，可視需要再調整 episodes、epsilon decay、target sync 等設定。
