# API_AviationStack_test
Simple test of the API with some data manipulation afterwards

The API_ACCESS_KEY should be provided as a os env variable.

# Notebook Overview:

The goal here was to check the API operation and test how the data transformation and sub selection was made.

# This notebook:
- retrieves 10 records of active flights, 
- selects a subset of columns, 
- renames columns
- modifies some column data
- calculates the size of the data batch 