# NYC Taxi Trip Duration - Kaggle competition (2017-09-15)

This repository contains experiments I made for the
[Kaggle New York City Taxi Trip Duration competition](https://www.kaggle.com/c/nyc-taxi-trip-duration).

![plot preview](http://i.imgur.com/8qdYUl3.jpg)

**See [the notebook on kaggle.com](https://www.kaggle.com/msotir/nyct-exploration-with-seaborn-and-datashader).**

## Getting started

Clone the repository:

```bash
git clone https://github.com/martinsotir/NYC_TaxiTripDuration_MS/blob/master/LICENSE
cd ./NYC_TaxiTripDuration_MS
```

Download Kaggle NYC 2016 taxi trip duration data:

* Put [train.zip](https://www.kaggle.com/c/nyc-taxi-trip-duration/download/train.zip) and [test.zip](https://www.kaggle.com/c/nyc-taxi-trip-duration/download/test.zip) in the ./data directory.

* Extract zip files:

    ```bash
    unzip ./data/test.zip -d ./data/
    unzip ./data/train.zip -d ./data/
    ```

To run notebooks, I recommend using a python virtualenv with conda :

```bash
conda env create -f environment.yml
source activate nyc-ms
jupyter notebook
```