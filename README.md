# Car Price Prediction Via Random Forest

An automotive group in your company has come to you with a problem. They are collecting data concerning used car sales and would like to provide their clients (salesman) with suggestions on what price to give for their cars, using a Proof of Concept.

Your final goal is to train a model that will suggest the price of the car. The notebook `otomoto_car_price_prediction_random_forest.ipynb` in this repository lays out in detail the approach, explaining the way of thinking, what factors have been taken into account, potential issues and how can this work be continued further. The report `report.pdf` summarizes the approach.

## Data source 
csv file containing info on cars (`car_price_prediction_data.csv.zip`)

## Fields
- make  : maker of the car (BMW, Toyota, etc.)
- model : model of the car
- vehicle_year : year when car was manufactured
- mileage : the total distance travelled by the car since its manufacture
- engine_capacity : the cylinder volume swept by all of the pistons of a piston engine, excluding the combustion chanbers. In cubic centimeters (cc)
- engine_power : units of horsepower
- gearbox : type of transmission
- fuel_type : type of fuel (e.g. diesel or petrol)
- damaged : is vehicle damaged (1) or not (0)
- is_business : the seller is a business (1) or an individual (0)
- target_price : price of the car in Zlotys (Polish currency)

## Steps taken
- Exploratory data analysis
- Data preprocessing
- Building a model
- Model evaluation
- Recommendation of further actions
