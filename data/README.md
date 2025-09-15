# Data Guide

**Source:** Kaggle — "Ecommerce Data" by Carrie  
https://www.kaggle.com/datasets/carrie1/ecommerce-data

This repo does **not** include the full raw CSV to keep the repo lightweight.

## Download with Kaggle CLI
1) Install: `pip install kaggle`
2) Create Kaggle API token (Kaggle → Account → Create New API Token) and place `kaggle.json` at:
   - macOS/Linux: `~/.kaggle/kaggle.json`  (then `chmod 600 ~/.kaggle/kaggle.json`)
3) Download & unzip into `data/raw/`:
   ```bash
   kaggle datasets download -d carrie1/ecommerce-data -p data/raw --unzip
