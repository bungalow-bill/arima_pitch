
## Exploring Time Series Data
by David Currie, Oct 2014   
<img src="./index_files/figure-slidy/firstslide.png" title="plot of chunk firstslide" alt="plot of chunk firstslide" style="display: block; margin: auto;" />

  [This application is available as a Shiny app.](https://geoanalytic.shinyapps.io/arima_models/)

---

### Goals
Forecasting from time series data is an interesting but difficult problem.  Using examples from the text [Forecasting: principles and practice](http://otexts.org/fpp/), written by [R. Hyndman](http://robjhyndman.com/) and G. Athanasopoulos, this interactive website allows the user to explore a few key topics.  The code is based on functions provided in the `Forecast` package.   

<img src="./index_files/figure-slidy/secondslide.png" title="plot of chunk secondslide" alt="plot of chunk secondslide" style="display: block; margin: auto 0 auto auto;" />


---

### Stationarity and Differencing   
Time series data can contain linear and cyclic trends, in addition to random signals, that make modelling difficult. Removing these effects prior to analysis allows the underlying signal to be observed. Pre-processing of the time series can be done using logs and sequential differencing.   

<img src="./index_files/figure-slidy/thirdslide.png" title="plot of chunk thirdslide" alt="plot of chunk thirdslide" style="display: block; margin: auto;" />

---

### ARIMA Models   
**A**uto**R**egressive **I**ntegrated **M**oving **A**verage models estimate the autocorrelations within the data in order to account for trends and cycles.  Very effective forecasts may be computed from such a model.   
<img src="./index_files/figure-slidy/fourthslide.png" title="plot of chunk fourthslide" alt="plot of chunk fourthslide" style="display: block; margin: auto;" />

---

### Data Exploration  
The [arima-models](https://geoanalytic.shinyapps.io/arima_models/) website permits the exploration and forecasting from 10 sample datasets.    

![screencapture](screencap.png)


