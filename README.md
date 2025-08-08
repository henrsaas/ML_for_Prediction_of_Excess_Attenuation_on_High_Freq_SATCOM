# Application of Machine Learning for Prediction of Atmospheric Attenuation Effects on High Frequency Satellite Communications in Near Future
# Master's thesis - May 2024
## Abstract
As the demand for globally available high throughput wireless communications is ever
increasing, there is a need to utilize higher frequency satellite bands more efficiently. In this
thesis we examine how to optimize a high frequency satellite communication system by
predicting the deterioration of a satellite communication channel through the use of
supervised machine learning (ML), satellite beacon measurements and openly available
State-Of-The-Art (SOTA) meteorological forecasts from the European Centre for Medium-
Range Weather Forecasts (ECMWF) [3].

  We propose the deployment of a hierarchical prediction approach, that first employ
our ML classification model which predicts whether any excess attenuation is present on a
channel, if there is, then our ML regression model predicts the magnitude in the form of the
mean, variability and maximum attenuation in the forecasted hour.

  The combined model we have developed through our proposed methodology is
fairly tailored to a single satellite communication channel at the location of the beacon
measurement site. However, our development pipeline is independent of both frequency
and location, and is easily adaptable to any other site, provided new measurement data.

  By comparing the performance of our ML model to that of a SOTA deterministic
model [6], we are able to determine the relevance of our work. The deterministic model is
undeniably much more comprehensive and utilizes a larger amount of data input. However,
our model shows promising results, especially the performance of our classification model
proves to be reasonably good. Yet, we observe that the deterministic model is able to
achieve more consistent and slightly better predictions than our regression model for a
similar task.

  The work done in this thesis proposes a machine learning approach for the
prediction of excess attenuation on a high frequency satellite communication channel. And
might serve as inspiration for future work within the field of satellite communications or
other similar fields traditionally governed by deterministic models or manual methods.

<img width="855" height="1029" alt="image" src="https://github.com/user-attachments/assets/005c437b-cafc-44e0-9c6d-924a90d7f9cd" />
