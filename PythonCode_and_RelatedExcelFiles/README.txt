Note: Please make sure that input files to programs are CSV files. Since output are xls sheet, manually convert them into csv files, by doing save as in excel sheet.


Codes to run in following sequence:
1. Data_Streaming: Calls the Foursquare API and then dumps the results in json file
2. Rating_Category: json parsing, finding rating and categories of every venue, creates excel sheet with rating and categories
3. Recommendation_Engine: map plotting, spatial joins to find boro and census track, finding nearest subway station, recommendation engine: same rating, not a same census track and same category of restaurant
4. Google_ID: Finding google place ID of places, output is excel sheet with all above things and google place ID
5. Wait_times: Finding wait times of restaurants and popular times.
Final excel sheet is : Combined_restaurant_waittimes.xlsx



