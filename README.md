# Sales-Predictions
![data info](https://user-images.githubusercontent.com/85266898/126203935-1f2ee550-04ba-40e9-a698-7fba9ff86342.PNG)
![lowfat](https://user-images.githubusercontent.com/85266898/126204434-1da55723-1b27-46f2-846e-1e9fc561dc4c.PNG)
                       
Using the Data provided, there was a couple issues with null data and inconsistent values.

![lowfatfix](https://user-images.githubusercontent.com/85266898/126204542-1667caa9-649d-47b6-b3e6-ffae2287172f.PNG)
![data fix](https://user-images.githubusercontent.com/85266898/126204659-3cf01421-e93b-432d-ab69-c97ca68b8bd7.PNG)

# Visualizations
After taking care of the data issues, it was time to look for correlations with the data.

![graph1code](https://user-images.githubusercontent.com/85266898/126205039-e9215578-a735-4d12-8dec-e20df26ddbc1.PNG)
![download](https://user-images.githubusercontent.com/85266898/126205048-089aedb6-9105-4da1-8f4f-4974fee7332f.png)
![graph2code](https://user-images.githubusercontent.com/85266898/126205200-c40b5016-7cfa-4750-99bb-f0704f460596.PNG)
![graph2](https://user-images.githubusercontent.com/85266898/126205210-d21d71bb-0a0c-433c-b634-7bfafe24be18.png)
![graph3code](https://user-images.githubusercontent.com/85266898/126205448-844ace06-fa96-4cd9-9f0b-3908b5e8214c.PNG)
![graph3](https://user-images.githubusercontent.com/85266898/126205465-b525dbb6-b54b-4d74-b0a2-2acffa1bb0ee.png)

After looking at the data and visualizations, it seems that Super Market Type1 is the most consistent as far as item sales and total Outlet Sales.

# Machine Learning Models
![machine1](https://user-images.githubusercontent.com/85266898/126206230-16981152-d71e-4d11-8b8c-6eb320c9ad80.PNG)

Preparing data for the machine learning model.

![machine2](https://user-images.githubusercontent.com/85266898/126206380-9d7fbdf7-3390-4d5c-b5bb-5cfd4cdbb33c.PNG)

Confirming shape and size of data.

![machine3](https://user-images.githubusercontent.com/85266898/126206417-00957646-df92-496c-bd85-664b03dec0e5.PNG)

Linear Regression model used to predict sales.

![machine4](https://user-images.githubusercontent.com/85266898/126206512-0e01248c-b147-4d71-882b-6eb17ecee153.PNG)

Using Train and Test split with a bagged trees model to predict sales.

![machine5](https://user-images.githubusercontent.com/85266898/126206624-35b598fa-e0b8-46f0-aded-d31698d0a780.PNG)
![machine5code](https://user-images.githubusercontent.com/85266898/126206640-4e6d7279-a468-4ff5-9441-246b5e62b68a.png)

A graph to show the best number of estimators to use for the model.

#Summary

To conclude with, After cleaning the data and looking at several visualizations, the SuperMarket Type1 is the best Market overall. We see the most item sales through this type of market and Total Revenue, but that does not make the other outlet types invalid. In areas that are heavily populated, SuperMarket Type1 is great because of its size and amount off items it offers. In lesser populated areas, Grocery Stores are great for lower volume sales.
