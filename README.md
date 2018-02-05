# TENZO UK SALES FORECASTING

```
What is this ?
```
This an automatic multi model platform for forecasting sales made for tenzo company by Telecom Paristech team

```
Tenzo
```

Tenzo is a start up that helps restaurants gain value from their data by connecting all data
sources and providing valuable data to owners, managers and store employees in real time
on mobile and web. More specifically, it helps restaurants increase procurement efficiency
with automated forecasting and dynamically find the right balance of delivery and in-store
resources.

Supervisors: 
```
Christian MOUYSSET
ADAM TAYLOR
```


Authors: 
```
Jawher Soudani

Xiaoyue LI

Yiting Sun

Yiying Jiang

Yuezhu Fang

```

Requiremnet :


[![Build Status](https://www.gotenzo.com/wp-content/themes/tenzo_new3/img/logo-big.png)](https://www.gotenzo.com/)

Python 3.6 or higher version


Go to [`Prophet Installation`](https://facebook.github.io/prophet/docs/installation.html) for Prophet prerequisites installations

Go to [`Tenso_Flow_Installation`](https://www.tensorflow.org/install/) for TensorFlow installations

Go to [`Keras_Installation`](https://keras.io/) for Keras installation



```
Integrated Platform develepped by our team
```

This final integrated model resumes all three models mentioned above in one automatic model
The characteristics of this model are :

• Multiple Models platform: when using this integrated model , it first asks the user
to choose one of the three models to start working with. The configuration and the
options proposed depend on this choice.
• Multiple options : Our integrated model propose multiple option do perform forecasting
on any number of days. The user can ask to do forecasting using dynamic method or
step by step method. Dynamic method forecast sales on any period of time using only
past data , the second method needs to retrain the model after each forecast using the
real value of the prediction.
• Multi-usage : this model can be used to describe and analyze data or to forecast future
sales
• Auto-Configuration : the model propose a high level configuration method that does
not require any technical knowledge to perform forecasting
• Auto-Error handler : the model handle or internal error so that is does not interrupt
forecasting when used for multiple locations.

```
How to run it
```

Super easy , you just run program runner.py  (command : python porgram_runner.py) in the same folder after you download this respository
It's guided , no knowledge needed to perform forecasting.

```
Can I modify this platform
```

The models in this platform are seprated , and each class is also seperated so you can add other models or delete them , or add other features , or add others options
This is a beta version that show a great results but it can be improved by adding graphical interface to it
We deleted random forest from this platform because it gave the results as LSTM

```
Why it asked for put an other variable with weather ?```

We put this to show you that the model can be modified to add any varibale you want
We used count_guest_number for that other varibale just to fill it but count_guest_number is not an external feature !!! be carefull


```
Some screen shots
```
This a screen shot showing how the first interface of the model and how it is super easy to configure (all the real work is done in background , you only give orders )

[![Build Status](https://lh6.googleusercontent.com/el6pUalRRt4V0xOEVMqi_sHz6LJ3KwoNOUoTwp_8EaD8bdNFxfZ2ruqLIH-O-MO6dCYriEbyGm551g=w1920-h928-rw)]


This a screen shot show the plot results that you got if you ask the model to plot results


[![Build Status](https://lh3.googleusercontent.com/cmKn1vcWtQtP_2HrLuGpwuMKtK7ZKDW9Ha5JssCprc6IY5OKT78qtLUZacoY6kvytwMG9XwM8OtQXQ=w1920-h928-rw)]

```
Some screen shots
```
This a screen shot show the MAPE calculated by the model ( you need to close the plot graph to get the MAPE)


[![Build Status](https://lh4.googleusercontent.com/Tp1xs9PV_sqGNw_Aif1mgPAH1EPcek_kov_VyovZZsBL5dwbm0KIDiyIU-yiv1zSKeFIKQnZ5Vr0pg=w1920-h928-rw)]

```
Final remarks 
```
The platform works for all locations
If you choose location and you want to add external feature , make sure that this location has external features , otherwise you will import empty table and the model won't work
If you choose not to add external features, no verification needed , it will always work.
Results are optimised for all models
Parameters are autotuned by the models
