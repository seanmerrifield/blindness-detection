# blindness-detection
A computer vision project for detecting diabetic retinopathy, a precursor to blindness

This is part of a [2019 Kaggle Competition on Blindness Detection](https://www.kaggle.com/c/aptos2019-blindness-detection).

## Insallation
After cloning the repository run:
```
pip install -r requirements.txt
```

Download the dataset:
```
mkdir data
kaggle competitions download -c aptos2019-blindness-detection -p ./data
```

Start the notebook:
```
jupyter notebook train.ipynb
```