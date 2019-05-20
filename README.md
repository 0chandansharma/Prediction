# Prediction


This project aims to predict the energy consumption by home appliances. With the advent of smart 
homes and rising need for energy management, existing smart home systems can benefit from accurate 
prediction. If the energy usage can be predicted for every possible state of appliances, then device 
control can be optimized for energy savings as well. I am implementing the prediction model by 
using methods of Deep Learning. Because the data are in time series one of the most popular method 
which I am going to introduce is LSTM (long short-term memory) which is recurrent neural network. 
Data used include measurements of temperature and humidity sensors in a time series format from a 
wireless network, weather from nearby airport station and recorded energy use of lighting fixtures
Appliance energy usage is the target variable while sensor data and weather data are the features.
The method discusses data filtering to remove non-predictive parameters and feature ranking. From 
the wireless network, the data from the kitchen, laundry and living room were ranked the highest in
importance for the energy prediction. The prediction models with only the weather data, selected the 
atmospheric pressure (which is correlated to wind speed) as the most relevant weather data variable in
the prediction. Therefore, atmospheric pressure may be important to include in energy prediction models
and for building performance modeling. Some other features included in my model which are time date and weekdays.
