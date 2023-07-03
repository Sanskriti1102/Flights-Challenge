# Flights Challenge (Flights Data Exploration Challenge)

This challenge contains a real-world dataset containing flight data from the US Department of Transportation.
### Contents :
The dataset contains observations of US domestic flights in 2013, and consists of the following fields:

    Year: The year of the flight (all records are from 2013)
    Month: The month of the flight
    DayofMonth: The day of the month on which the flight departed
    DayOfWeek: The day of the week on which the flight departed - from 1 (Monday) to 7 (Sunday)
    Carrier: The two-letter abbreviation for the airline.
    OriginAirportID: A unique numeric identifier for the departure airport
    OriginAirportName: The full name of the departure airport
    OriginCity: The departure airport city
    OriginState: The departure airport state
    DestAirportID: A unique numeric identifier for the destination airport
    DestAirportName: The full name of the destination airport
    DestCity: The destination airport city
    DestState: The destination airport state
    CRSDepTime: The scheduled departure time
    DepDelay: The number of minutes departure was delayed (flights that left ahead of schedule have a negative value)
    DelDelay15: A binary indicator that departure was delayed by more than 15 minutes (and therefore considered "late")
    CRSArrTime: The scheduled arrival time
    ArrDelay: The number of minutes arrival was delayed (flights that arrived ahead of schedule have a negative value)
    ArrDelay15: A binary indicator that arrival was delayed by more than 15 minutes (and therefore considered "late")
    Canceled: A binary indicator that the flight was canceled
    
### Flight Delays Analysis :
The challenge is to explore the flight data to analyze possible factors that affect delays in the departure or arrival of a flight.

    Start by cleaning the data.
        1. Identify any null or missing data, and impute appropriate replacement values.
        2. Identify and eliminate any outliers in the DepDelay and ArrDelay columns.
    Explore the cleaned data.
        1. View summary statistics for the numeric fields in the dataset.
        2. Determine the distribution of the DepDelay and ArrDelay columns.
        3. Use statistics, aggregate functions, and visualizations to answer the following questions:
            a.  What are the average (mean) departure and arrival delays?
            b. How do the carriers compare in terms of arrival delay performance?
            c. Is there a noticeable difference in arrival delays for different days of the week?
            d. Which departure airport has the highest average departure delay?
            e. Do late departures tend to result in longer arrival delays than on-time departures?
  # 
  #### Flight Delays Analysis Challenge from Microsoft Learn: Analyzing factors affecting delays in flight departure and arrival using US Department of Transportation's real-world flight data.
  
