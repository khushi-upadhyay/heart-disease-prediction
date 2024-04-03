This project aims to develop a comprehensive heart disease prediction system. The system incorporates a machine learning model that predicts heart disease based on user input. The core requirements for this task include:

1. **Integration with MongoDB**: Establish a connection between the model and a MongoDB database. This database will store user inputs as well as the prediction results.

2. **User Interface**: Implement a user interface for input collection. While Streamlit is acceptable, creating the interface using FastAPI is preferred for its versatility and performance. The interface should allow users to submit their data, which is then stored in the database.

3. **Model Prediction and Data Handling**: After storing the input data in the database, the system should retrieve this data to perform the prediction. Finally, save the prediction outcome back into the database.
