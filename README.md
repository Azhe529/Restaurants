# Government Digital Services, CC4.0

## Background

Steven is a travel blogger that intends to create a travel food series. He is looking at data from Zomato for inspiration. He wants to find restaurants that have good user ratings and interesting past events. This project is designed to assist Steven in gathering valuable insights to create informative blog posts.

## Data used
- `./Data/Country-Code.xlsx` -- Storing information about country ids and country names.
- [Json data on lists of restaurants](https://raw.githubusercontent.com/Papagoat/brain-assessment/main/restaurant_data.json)

## Environment requirement
To run the Jupyter Notebook successfully, ensure that your Python environment meets the following requirements:

- Python version 3.10 or later
- Required packages: pandas, numpy, requests, matplotlib
You could install the packages by running the following code in jupyter notebook with the following code
```python
pip install pandas numpy requests matplotlib openpyxl
``` 


## Source code
The source code of the projected is filed in `./Sun Sizhe.ipynb`. 

Through running the code in the notebook, the csv files required for the first 2 questions will be stored in `./Results` as stated in the following section, while the answer to the third question could be found in the __Conclusion__ section under __Question 3__ in the notebook.

## Results
There are two csv files stored in `./Results` folder.
- `restaurants.csv` -- Containing information of restaurants on:
    - Restaurant Id
    - Restaurant Name
    - Country
    - City
    - User Rating Votes
    - User Aggregate Rating (in float)
    - Cuisines
- `restaurant_events.csv` -- Containing information of restaurant events happening in April 2019 on:
    - Event Id
    - Restaurant Id
    - Restaurant Name
    - Photo URL
    - Event Title
    - Event Start Date
    - Event End Date
