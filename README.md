# FinTech Module 14 Challenge: Machine Learning Trading Bot


Trading strategy where we try to predict the direction of the future price changing. 
We use Machine Learning Algorithms (Simple Moving Averages) to predict direction of future returns.

### SVM short is 4 and long is 100.

![SVM short=4 long=100 Classification Report](Resources/SVM_short_4_long_100_baseline_classification_report.png)
![SVM short=4 long=100](Resources/SVM_short_4_long_100_baseline.png)
![SVM short=4 long=100 Shifted](Resources/SVM_short_4_long_100_baseline_shifted.png)

### AdaBoost short is 4 and long is 100.
![AdaBoost short=4 long=100 Classification Report](Resources/Adaboost_short_4_long_100_baseline_classification_report.png)
![AdaBoost short=4 long=100](Resources/Adaboost_short_4_long_100_baseline.png)
![AdaBoost short=4 long=100 Shifted](Resources/Adaboost_short_4_long_100_baseline_shifted.png)

## Increase Training Time period to 2 years (4, 2015 to end of 3, 2017) 

![SVM short=4 long=100 train 4,2015 to 3,2017 Classification Report](Resources/SVM_short_4_long_100_train_4_2015_3_2017_classification_report.png)
![SVM short=4 long=100 train 4,2015 to 3,2017](Resources/SVM_short_4_long_100_train_4_2015_3_2017.png)
![SVM short=4 long=100 train 4,2015 to 3,2017 Shifted](Resources/SVM_short_4_long_100_train_4_2015_3_2017_shifted.png)

### Adaboost short is 4 and long is 100

![AdaBoost short=4 long=100 train 4,2015 to 3,2017 Classification Report](Resources/Adaboost_short_4_long_100_train_4_2015_3_2017_classification_report.png)
![AdaBoost short=4 long=100 train 4,2015 to 3,2017](Resources/Adaboost_short_4_long_100_train_4_2015_3_2017.png)
![AdaBoost short=4 long=100 train 4,2015 to 3,2017 Shifted](Resources/Adaboost_short_4_long_100_train_4_2015_3_2017_shifted.png)

### SVM short is 4 and long is 50

![SVM short=4 long=50 train 4,2015 to 4,2017 Classification Report](Resources/SVM_short_4_long_50_train_4_2015_4_2017_classification_report.png)
![SVM short=4 long=50 train 4,2015 to 4,2017](Resources/SVM_short_4_long_50_train_4_2015_4_2017.png)
![SVM short=4 long=50 train 4,2015 to 4,2017 Shifted](Resources/SVM_short_4_long_50_train_4_2015_4_2017_shifted.png)

### Adaboost short is 4 and long is 50

![AdaBoost short=4 long=50 train 4,2015 to 4,2017 Classification Report](Resources/Adaboost_short_4_long_50_train_4_2015_4_2017_classification_report.png)
![AdaBoost short=4 long=50 train 4,2015 to 4,2017](Resources/Adaboost_short_4_long_50_train_4_2015_4_2017.png)
![AdaBoost short=4 long=50 train 4,2015 to 4,2017 Shifted](Resources/Adaboost_short_4_long_50_train_4_2015_4_2017_shifted.png)

## Test runs 

![Test Results 1](Resources/test_results_various_runs_1.png)
![Test Results 2](Resources/test_results_various_runs_2.png)

## Summary

The overall best model out of the models explored is the baseline SVM model because it has one of the best overall accuracies and is able to predict some key negative returns resulting in one of the best overall returns. Although, it may not be able to predict all the future downturns and may result in adverse performance because it is pretty bad at predicting negative returns. A baseline Adaboost trained on oversampled positive events may have performed better than the baseline SVM model for the overall returns. Oversampling for the Adaboost needs to be tried out.

---

## Usage

To use the Application, download and open the **machine_learning_trading_bot.ipynb** 

---

## Contributors

Grigory Timofeev

[E-mail](fintech_github_challenge14@unloca.com)

---

## License

The MIT License (MIT)

Copyright (c) 2022 Grigory Timofeev

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
