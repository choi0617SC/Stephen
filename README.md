# Small AI Project — Building AI 練習範例

目的
- 為 Building AI 課程準備的練習專案：練習 Python 機器學習流程（資料處理、訓練、評估、記錄）。
- 使用簡單的 scikit-learn 範例（可擴充到 TensorFlow / PyTorch）。

檔案與說明
- `requirements.txt`：必需套件。
- `src/`：程式碼（data loader、model、train）。
- `notebooks/`：Jupyter notebook 練習。
- `data/`：存放資料（不要把大型資料上傳到 Git）。

快速開始（本機）
1. 建立 virtualenv 並安裝：
   ```
   python -m venv venv
   source venv/bin/activate      # macOS / Linux
   venv\Scripts\activate         # Windows
   pip install -r requirements.txt
   ```
2. 執行訓練範例：
   ```
   python src/train.py --model logistic --test-size 0.2 --random-state 42
   ```
3. 查看 experiments/ 或直接在 notebooks/ 進行互動式實驗。

欲望的擴充
- 換用自訂 dataset
- 加入超參數搜尋 (GridSearch / Optuna)
- 換成深度學習框架 (PyTorch / TensorFlow)
