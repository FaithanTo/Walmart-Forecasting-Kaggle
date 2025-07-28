\# Forecasting Sales for Walmart (\[Kaggle](https://www.kaggle.com/competitions/m5-forecasting-accuracy))



\*\*A neural network pipeline to forecast 28-day item-level sales for Walmart using time series modeling and PyTorch.\*\*



This project tackled the M5 Forecasting Accuracy challenge on Kaggle, where the goal was to predict daily sales across 30,000+ Walmart SKUs. I designed a custom PyTorch LSTM pipeline with engineered time series features, leveraging hierarchical statistics and custom batching for scalable training. The model outperformed a naive baseline by 21%, emphasizing both forecasting accuracy and efficient sequence generation.



\## 🔧 Tools Used

\- Jupyter Notebook

\- Python: Pandas, NumPy, Polars, Scikit-learn, PyTorch, Matplotlib

\- Deep Learning: LSTM (Long Short-Term Memory), Embedding Layers

\- Feature Engineering: Hierarchical Averages, Rolling Statistics, Label Encoding, Cyclical Encoding

\- Data Processing: Parquet I/O, Time Series Partitioning, Sequencing, Batch Streaming

\- Evaluation: RMSE, WRMSSE



\## 💡 Key Highlights

\- Engineered sequence batches across 305 parquet files for scalable training

\- Used custom data loaders and memory-optimized batching

\- Beat naive forecasting baseline by 21% on evaluation dataset



> "Yes, it is indeed possible to create a fancy, but overcomplicated forecasting model."

