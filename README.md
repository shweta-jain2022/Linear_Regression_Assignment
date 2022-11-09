# **BIKE SHARING SERVICE**

> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
> In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


## **BUSINESS GOAL**
> To develop a model for demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. 
 

## **DATASET PROVIDED HAS THE FOLLOWING INFORMATION:**
> instant: Record index
> dteday : Date
> season : Season (1:spring, 2:summer, 3:fall, 4:winter)
> yr : Year (0: 2018, 1:2019)
> mnth : Month ( 1 to 12)
> holiday : Whether day is a holiday or not 
> weekday : Day of the week
> workingday : If day is neither weekend nor holiday is 1, 		          otherwise is 0.
> weathersit : Weather situation (clear/ mist/ rain/ snow)
> temp : Temperature in Celsius
> atemp: Feeling temperature in Celsius
> hum: Humidity
> windspeed: Wind speed
> casual: Count of casual users
> registered: Count of registered users
> cnt: Count of total rental bikes including both casual and registered


## **TARGET/DEPENDENT VARIABLE**
> cnt: Count of total rental bikes including both casual and 	 	registered


## **FINAL MODEL**
> cnt = 0.2045 + 0.2445yr + 0.0605workingday -   	0.1174windspeed + 0.2215summer + 0.2760fall + 0.2089winter 	+ 0.0656mar + 0.0978may + 0.1155jun + 0.0678aug + .1205sep 	+ 0.1162oct + 0.0664mon - 0.0903mist -0.3194rain


## **R2 SCORE**
> On training set - 0.804
> On test set - 0.769


## **CREATED BY**
> Shweta Jain<br>


