
eBay Car Sales Data Cleaning and Analysis

Project Overview
This project focuses on cleaning and analyzing a dataset of used cars from eBay Kleinanzeigen, a German online marketplace. The dataset was scraped and uploaded to Kaggle, containing information on 50,000 car listings. The goal of this project is to clean the data, explore key features, and analyze trends that impact the prices of used cars.

Dataset
The dataset includes the following key columns:
- dateCrawled: The date when the ad was first crawled.
- name: The name of the car.
- seller: Type of seller (private or dealer).
- offerType: Type of listing.
- price: The listed price of the car.
- vehicleType: The type of vehicle.
- yearOfRegistration: The year the car was first registered.
- gearbox: Transmission type.
- powerPS: Car power in PS.
- odometer: Distance driven (in kilometers).
- fuelType: Type of fuel used.
- brand: The car’s brand.
- notRepairedDamage: Whether the car has unrepaired damage.
- dateCreated: The date the ad was created.
- lastSeen: When the crawler last saw the ad online.

Project Tasks
1. Data Cleaning
- Translation of German Categorical Data: Columns such as vehicleType, gearbox, and fuelType contained German words, which were translated into English for better understanding.
- Date Standardization: Columns containing dates were converted from strings to a consistent numeric format for easier manipulation and analysis.
- Keyword Extraction: Key information from the name column, such as car brands and models, was extracted to create a more structured dataset.

2. Data Analysis
- Common Brand/Model Combinations: We identified the most frequently listed brand/model combinations in the dataset, with Volkswagen, BMW, and Opel being the most popular brands.
- Price vs. Mileage: We analyzed how car prices varied with mileage by grouping odometer_km values. The analysis showed that cars with lower mileage were priced higher, and prices dropped significantly as mileage increased.
- Impact of Unrepaired Damage: The analysis revealed that cars with unrepaired damage were much cheaper than those without damage, indicating the importance of a car's condition in determining its resale value.

Key Insights
- Volkswagen was the most frequently listed brand, with the Golf being the most popular model.
- Cars with lower mileage (0-50,000 km) commanded much higher prices compared to those with higher mileage.
- Cars with unrepaired damage were significantly cheaper, showing that damage greatly affects the resale value of vehicles.

Requirements
To run the notebook, you'll need the following:
- Python 3.x
- Pandas library

How to Run
1. Ensure that the dataset is loaded correctly (as autos.csv).
2. Run the cells in the notebook to clean and analyze the dataset.
3. The results, including insights into brand/model combinations, mileage vs. price trends, and the impact of damage on pricing, will be displayed.

Conclusion
This project demonstrates a structured approach to cleaning and analyzing a dataset of used cars. By following the steps outlined in the notebook, users can gain insights into key factors that influence car prices, such as brand, mileage, and condition.
