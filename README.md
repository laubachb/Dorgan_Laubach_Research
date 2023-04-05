# Spectrometer Project

The objective of this project is to develop an algorithm/software that can accurately classify NIR data from a hand-held spectrometer. The data comprises of four categories: HDPE (1), LDPE (2), LLDPE (3), and PP (4). The algorithm first sorts through directories, extracts files, and cleans the data. Each data image includes the reference signal and the sample signal, both of which are unitless. Labels are then assigned to each image based on the corresponding category, which enables a supervised learning approach for the machine learning model. After cleaning the data, the model is trained using a logistic regression approach with train-test methodology. Subsequently, the model is validated by evaluating the mean squared error (MSE), R-squared, and mean absolute error (MAE) and the results are further visualized. However, given the limited amount of data collected, the model's accuracy is 100%, which could indicate the need for additional data collection. Research papers are included for additional background information.

Previous work on this project: https://drive.google.com/drive/u/2/folders/1Fdun9Z9YGgZgObM7RfFzQTuKiDxgCS7Z <br>
Inno Spectra: https://inno-spectra.hct.tw/index_en <br>
Other work: https://github.com/arminstr/reremeter
