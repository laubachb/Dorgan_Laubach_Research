# Spectrometer Project

The goal of this project is to create an algotithm/software that classifies NIR data from the given hand held spectrometer. The data has four classifications: HDPE (1), LDPE (2), LLDPE (3), and PP (4). The algorithm works by first sorting through directories, pulling files, and cleaning data. Each image of data includes the reference signal (unitless) and the sample signal (unitless). Once each image has been pulled, labels are created for the images based on the proper species. This yields itself to a supervised learning approach for the ML model. Once the data has been cleaned, the model is built using train test 


Previous work on this project: https://drive.google.com/drive/u/2/folders/1Fdun9Z9YGgZgObM7RfFzQTuKiDxgCS7Z
Inno Spectra: https://inno-spectra.hct.tw/index_en
Other work: https://github.com/arminstr/reremeter
