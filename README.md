**BANK MARKETING CAMPAIGN**
#### **Problem Statement**

##### **Context**
   Produk keuangan yang digunakan oleh masyarakat semakin beragam, salah satunya adalah deposito berjangka yang banyak dikenal. Deposit berjangka adalah ketika seseorang menyimpan uang di bank atau lembaga keuangan dan hanya bisa ditarik setelah beberapa waktu. Sebagai imbalannya, nasabah akan mendapatkan bunga tetap sesuai dengan jumlah uang yang disimpan.
   
   Namun, bank harus bersaing agar tidak kehilangan nasabah. Salah satu cara yang digunakan adalah dengan melakukan kampanye pemasaran melalui panggilan telepon untuk menawarkan deposito berjangka. Jika nasabah setuju, mereka akan menandai variabel target dengan `yes` sama dengan `1`, jika tidak setuju, maka akan ditandai dengan `no` sama dengan `0`.

   Keterangan target:

   0 : Tidak menaruh deposit

   1 : Menaruh deposit

##### **Stakeholder** 
   - Bank's Marketing Manager 
   - Bank's Marketing Team.

##### **Problem**
   
   Bank ingin meningkatkan efisiensi kampanye penawaran deposito dengan cara menargetkan calon nasabah yang berpotensi tertarik, karena jika menawarkan deposito kepada semua nasabah tanpa penyaringan, maka akan menghabiskan waktu dan biaya yang lebih banyak.
   
------------

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third-party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- Documentation of project
    │
    ├── notebooks          <- Jupyter notebooks. The naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `bank-marketing-campaign`.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results-oriented visualizations
    │       └── visualize.py
    │
    └── references         <- Data dictionaries https://drive.google.com/drive/folders/13lrEDlKfnTPNREfGLBaYGYf8dSjHBzfW , https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset


--------
