## Cars4U: Used Car Market Insights and Pricing Prediction

Nov 20 2022 | Hugo Hiraoka | hhiraoka.w@gmail.com

A linear regression model to predict prices of used cars. This is a supervised learning model.

### Context

There is a huge demand for used cars in the Indian Market today. As sales of new cars have slowed down in the recent past, the pre-owned car market has continued to grow over the past years and is larger than the new car market now. Cars4U is a budding tech start-up that aims to find footholes in this market.

In 2018-19, while new car sales were recorded at 3.6 million units, around 4 million second-hand cars were bought and sold. There is a slowdown in new car sales and that could mean that the demand is shifting towards the pre-owned market. In fact, some car sellers replace their old cars with pre-owned cars instead of buying new ones. Unlike new cars, where price and supply are fairly deterministic and managed by OEMs (Original Equipment Manufacturer / except for dealership level discounts which come into play only in the last stage of the customer journey), used cars are very different beasts with huge uncertainty in both pricing and supply. Keeping this in mind, the pricing scheme of these used cars becomes important in order to grow in the market.

![used car image](https://i.imgur.com/6ikhTCQ.jpg)
AI generated image

We will come up with a pricing model that can effectively predict the price of used cars and can help the business in devising profitable strategies using differential pricing. For example, if the business knows the market price, it will never sell anything below it.



### Objectives

We will explore and visualize the dataset, build a pricing model using Linear Regression that can effectively predict the price of used cars and we will generate a set of insights and recommendations that can help the business in devising profitable strategies. For example, if the business knows the market price, it will never sell anything below it.

### Key Questions

- What are the factors that influence the selling price of a used car?
- What is a good predictive model that outputs the selling price of a used car?

### **Data Dictionary**

The data contains the different attributes of used cars sold in different locations. The detailed data dictionary is given below.

- S.No.: Serial number
- Name: Name of the car which includes brand name and model name
- Location: The location in which the car is being sold or is available for purchase (cities)
- Year: Manufacturing year of the car
- Kilometers_driven: The total kilometers (a unit used to measure length or distance) driven in the car by the previous owner(s)
-Fuel_Type: The type of fuel used by the car (Petrol, Diesel, Electric, CNG, LPG)
-Transmission: The type of transmission used by the car (Automatic/Manual)
-Owner: Type of ownership
-Mileage: The standard mileage offered by the car company in kmp/l or km/kg
-Engine: The displacement volume of the engine in CC
-Power: The maximum power of the engine in bhp
-Seats: The number of seats in the car
-New_Price: The price of a new car of the same model in INR Lakhs (1 Lakh INR = 100,000 INR)
-Price: The price of the used car in INR Lakhs
