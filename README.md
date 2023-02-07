# Deep Learning For Air Quality Prediction
Deep learning model to predict PM2.5 concentration in Bangkok, Thailand by using meteorological data which collected by Meteorological Department and Pollution Control Department.

Created by using Python language with Google Colab

## Table of contents
* [Team Member](#team-member)
* [General info](#general-info)
  * [Abstract](#abstract)
  * [Libraries](#libraries)
* [Awards](#awards)
* [Reference](#reference)

## Team Member 
- [Krittin Thirasak](https://github.com/krittintrs) : research and develop deep learning model
- [Teerawat chuaphanngam](https://github.com/phukaokub) : data research and presentation
- Wasupol Hengsritawat : scientific research and graphic design

## General info
This is a high school project which mainly focus on how to develop deep learning model and adapt the model to predict PM2.5 concentration. We used meteorological data an previous day PM2.5 concentration as input for the model. The data is collected by Meteorological Department and Pollution Control Department. The model we use is a feed-forward neural network with 4-fold validation.  

### Abstract
Air pollution has been concerned as one of the major problems after fine particulate matter with a diameter less
than 2.5 microns (PM2.5) concentrations have been continuously increasing in recent years. The high concentration of PM2.5 has a crucial effect on health, especially in the respiratory system. Predicting PM2.5 concentrations in time could help
the government in managing the air quality problem in some ways. In this work, we studied deep learning models to predict
PM2.5 concentrations in Bangkok, Thailand. We used 10 features consist of meteorological data and ground-measured
PM2.5 in the modeling. These data were used to train models in many different network architectures starting from 5
neurons until we found the best model. Our final model has 3 layers with 12 neurons in each layer. After the final test was
evaluated, we obtained the model performance which were R2 = 0.68, MAE = 6.75 μg/m3 (25.13 % error of average of PM2.5 concentrations), and RMSE = 10.06 μg/m3. Our model is considered to be in moderate performance. From the result,
we conclude that the weather can be used for predicting PM2.5 concentrations in deep learning model. Furthermore, we
study about the relations between amount of data and model performance by testing with different amount of data sets from
one to six months. Our results tend to indicate that model performance varies with the amount of data sets. Thus, this work
could be improved by using more various features and a larger amount of data.

### Libraries
- `numpy` = calculate evaluation metrics
- `pandas` = dataframe 
- `sklearn` = prepare dataset
- `keras` = create deep learning model
- `matplotlib` = plot the result

## Awards
-	**Gold Medal:** Oral Presentation from ICYS
-	**Gold Medal:** Oral Presentation of Technology and Computer from 10th SCiUS Forum
- **Silver Medal:** Oral Presentation from the 1st International Conference for Students in Science and Innovation
-	**Bronze Medal:** Poster Presentation from the 1st International Conference for Students in Science and Innovation

## Reference
- M. Zamani Joharestani, C. Cao, X. Ni, B. Bashir, and S. Talebiesfandarani, Atmosphere **10**, 373 (2019). [link](https://doi.org/10.3390/atmos10070373)
- F. Chollet, Deep Learning with Python (Manning, Shelter Islands, 2018), pp. 1-116.
- B. Brunekreef and S. T Holgate, The Lancet **360**, 1233-1242 (2002). [link](10.1016/S0140-6736(02)11274-8)
