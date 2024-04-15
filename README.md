# Text-Summarization-Practice-Project

## Steps for developing this project


1. First we need to create custom log for that we need to add some code in the src/textSummarizer/logging/__init__.py file

2. Now we need to add some functions in the src/textSummarizer/utils/common.py file
    - Add a function which reads all the yaml files
    - Add a function to create directories
    - Add a function which returns the size of the file

3. Write code in config/config.yaml for creating artifacts folder and for data ingestion

4. ## Data Ingestion

 - Now we need to do data ingestion in research forlder, In which we are going to download and unzip the data file
 - Now update the configuration.py file
 - Now create a pipeline name stage_01_data_ingestion.py
 
5. ## Data Validation 

 - Now we are gonna validate our data
 - First update config.yaml file by creating data validation function
 - update entitties by adding data validation in __init__.py file
 - Now create components of data validation.

6. ## Data Transformation

 - Now we are gonna perform our data transformation in the notebook and then add it to the respected file.
 - Update config.yaml and then run the notebook
 - Update the entity file
 - Update configuration.py file
 - Add a new componenet for data
 - Add a new stage in pipeline folder for data transformation

7. ## Model Training 
 - Now we are gonna train our model
 - Update config.yaml file
 - Update params.yaml file
 - Update entity
 - Upgrade cofiguration.py file
 - create a component model_trainer.py
 - Create pipeline
 - Update main.py file