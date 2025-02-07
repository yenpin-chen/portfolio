# 巴西電子商務資料預處理

此儲存庫包含一個用於預處理巴西電子商務資料的 Jupyter Notebook。資料集來源於 Kaggle，並透過 SQL 進行資料預處理，以便進行探索性資料分析和機器學習。

## 功能
- **資料下載**：使用 `kagglehub` 自動從 Kaggle 下載資料集。
- **SQL 整合**：使用 `DuckDB` 進行高效的資料操作。
- **Pandas 相容性**：在 Python 中處理資料以進行進一步分析。
- **檔案管理**：管理多個 CSV 檔案以提取有價值的資訊。

## 安裝

要執行此專案，請確保您已安裝 Python，並安裝以下依賴項：

```bash
pip install duckdb pandas kagglehub
```

## 使用方法

1. 複製此儲存庫：
   ```bash
   git clone https://github.com/your_username/brazilian-ecommerce-preprocessing.git
   cd brazilian-ecommerce-preprocessing
   ```

2. 開啟 Jupyter Notebook：
   ```bash
   jupyter notebook Brazilian_E_Commerce_Data_Pre_proccess.ipynb
   ```

3. 按照 Notebook 中的步驟操作：
   - 從 Kaggle 下載資料集。
   - 使用 SQL 和 Python 加載並預處理資料。

## 資料集資訊

此專案使用的資料集包含以下資訊：
- **客戶**：客戶的人口統計和地理資料。
- **訂單**：訂單詳細資訊、時間戳記和狀態。
- **產品**：產品分類和描述。
- **評論**：客戶評論和評分。

## 專案結構

```
|-- Brazilian_E_Commerce_Data_Pre_proccess.ipynb
|-- README.md
```

- **Brazilian_E_Commerce_Data_Pre_proccess.ipynb**：主要的資料預處理 Notebook。
- **README.md**：專案的文件說明。

## 授權

此專案基於 Apache-2.0 許可證。詳情請參閱 LICENSE 文件。

## 資料來源

- **資料集**：[Olist 的巴西電子商務公開資料集](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)。
- **工具**：`duckdb`、`pandas`、`kagglehub`。

