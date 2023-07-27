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

1. model: Contains the data model for FX deals (FxDeal).
2. dto: Contains the dto data model for FX deals (FxDealOrderDTO)
3. repository: Contains the FxDealRepository.
4. utils: Contains the utility class for mapping and validation.
5. exception: Contains the custom exception handling class.
6. controller: Contains the controller class housing the endpoints
7. service: Contains the service interface and implementation class.

# Access the application:

  The application will be available at http://localhost:(--port).
  
  1.Import FX deals:

  Send POST requests to http://localhost:(--port)/api/deals/fxDeals with valid JSON data containing the FX deal details. The API will return a response with the created FX deal   details.
  
2.Retrieve FX deals:

  Send GET requests to http://localhost:(--port)/api/getAllFxDeals to get a list of all stored FX deals.
  Send GET requests to http://localhost:(--port)/api/fxDeals/{id} to retrieve an individual FX deal by its ID.

# Contributing
We welcome contributions to the FX Deals Data Warehouse project. If you have any ideas, bug fixes, or enhancements, please submit a pull request.
