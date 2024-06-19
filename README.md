# TAA_Airbnb_Price_Prediction

This project was made for the TAA (Machine Learning) discipline and also used for Informatics Project discipline. Our case study was to predict AirBnb prices with Lisbon data. The implementation of the code was inspired by [this kaggle](https://www.kaggle.com/code/maurylukas/helping-people-in-lisbon-to-predict-airbnb-prices), which also provided the dataset for 2021. The data from 2023 was directly obtained from [InsideAirBnb](https://insideairbnb.com/).

The file organization is:

- airbnb_lisbon: main file, has the initial model using 2021 and 2023 Lisbon data and predicting with tree-based models.
- airbnb_lisbon_svm: predictions for 2021 data using other models like support vector regression and k-neighbours.
- data_visualization: script made for visualizing prices troughout different months and years.
- airbnb_lisbon_test_Porto: training with all Lisbon properties and testing with Porto.
- airbnb_lisbon_cv: test using cross validation on the same data from airbnb_lisbon