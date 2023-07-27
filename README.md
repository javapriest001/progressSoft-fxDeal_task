# progressSoft-fxDeal_task
This project aims to develop a data warehouse for Bloomberg to analyze Foreign Exchange (FX) deals. The system will accept FX deal details, validate the data, persist it into a database, and provide the necessary functionality to retrieve and analyze the FX deals.

# Technologies
1. Java
2. Springboot
3. maven
4. docker
5. mysql

# Project Structure
The project is organized into several packages:

model: Contains the data model for FX deals (FxDeal).
dto: Contains the dto data model for FX deals (FxDealOrderDTO)
repository: Contains the FxDealRepository.
utils: Contains the utility class for mapping and validation.
exception: Contains the custom exception handling class.
controller: Contains the controller class housing the endpoints
service: Contains the service interface and implementation class.

# Accessing The ApplicationAccess the application:

The application will be available at http://localhost:5000.
Import FX deals:

Send POST requests to http://localhost:5000/api/deals/fxDeals with valid JSON data containing the FX deal details. The API will return a response with the created FX deal details.
Retrieve FX deals:

Send GET requests to http://localhost:8080/api/getAllFxDeals to get a list of all stored FX deals.
Send GET requests to http://localhost:8080/api/fxDeals/{id} to retrieve an individual FX deal by its ID.
