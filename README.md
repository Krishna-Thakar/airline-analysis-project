# Airline Analysis Project

This repository contains SQL scripts for basic and advanced analysis of airline operations and passenger data, as well as a Power BI dashboard visualizing key insights.

## Files in the Repository

1. **basic_analysis.sql:** Contains SQL queries for basic data analysis on airline operations and passenger data.
2. **advanced_analysis.sql:** Contains SQL queries for advanced data analysis, including trends and growth rates.
3. **airline_dashboard.pbix:** A Power BI dashboard visualizing key metrics and insights from the airline data.
4. **airports2.csv:** The dataset used for the analysis, containing information about flights, passengers, distances, and more.

## SQL Analysis

### Basic Analysis
The basic analysis script (`basic_analysis.sql`) covers the following problem statements:
1. **Total Passengers by Route:** Calculate the total number of passengers for each pair of origin and destination airports.
2. **Average Seat Utilization:** Calculate the average seat utilization for each flight.
3. **Top Routes by Passenger Volume:** Determine the top 5 origin and destination airport pairs with the highest total passenger volume.
4. **Flights and Passengers by City:** Calculate the total number of flights and passengers departing from each origin city.
5. **Total Distance by Origin Airport:** Calculate the total distance flown by flights originating from each airport.
6. **Monthly and Yearly Trends:** Group flights by month and year to calculate the number of flights, total passengers, and average distance traveled.
7. **Underutilized Routes:** Identify routes where the passenger-to-seats ratio is less than 0.5.
8. **Top Origin Airports:** Determine the top 3 origin airports with the highest frequency of flights.
9. **Key Contributors to Bend, OR:** Identify the cities (excluding Bend, OR) that send the most flights and passengers to Bend, OR.
10. **Longest Flight Route:** Identify the longest flight route in terms of distance traveled.

### Advanced Analysis
The advanced analysis script (`advanced_analysis.sql`) covers the following problem statements:
1. **Most and Least Busy Months:** Determine the most and least busy months by flight count across multiple years.
2. **Year-over-Year Passenger Growth:** Calculate the year-over-year percentage growth in the total number of passengers for each route.
3. **Consistent Growth Routes:** Identify routes that have demonstrated consistent year-over-year growth in the number of flights.
4. **Top Utilization Airports:** Determine the top 3 origin airports with the highest weighted passenger-to-seats utilization ratio.
5. **Peak Traffic Months:** Identify the peak traffic month for each origin city based on the highest number of passengers.
6. **Declining Routes:** Identify the routes that have experienced the largest decline in passenger numbers year-over-year.
7. **Underperforming Routes:** List all routes that had at least 10 flights but maintained an average seat utilization of less than 50%.
8. **Longest Average Distance Routes:** Calculate the average flight distance for each city-to-city pair and identify the routes with the longest average distance.
9. **Yearly Trends in Flights and Passengers:** Calculate the total number of flights and passengers for each year and the percentage growth compared to the previous year.
10. **Busiest Routes by Distance:** Identify the top 3 busiest routes based on the total distance flown, weighted by the number of flights.

## Power BI Dashboard

The Power BI dashboard provides visual insights into key metrics and trends in airline operations and passenger data. Key elements include:
- Total Passengers
- Total Distance
- Number of Flights
- Destinations Airport
- Origins Airport
- Sum of Passengers by Origin Airport (Map)
- Sum of Passengers by Origin Airport (Bar Chart)
- Quarterly Flight Counts (Line Chart)
- Total Passengers by Year (Area Chart)

### Access the Power BI Dashboard
You can view the Power BI dashboard [here](https://drive.google.com/file/d/1IB6SLrczIdkNBNWgXkjWowxZDs_FXu8q/view?usp=sharing).

## Dataset

The dataset (`airports2.csv`) contains the following columns:
- Origin_airport
- Destination_airport
- Passengers
- Seats
- Flights
- Distance
- Fly_date
- Origin_city
- Destination_city

## How to Use

1. **Clone the Repository:**
    ```shell
    git clone https://github.com/Krishna-Thakar/airline-analysis-project.git
    ```

2. **SQL Analysis:**
   - Import the `airports2.csv` dataset into your SQL environment.
   - Run the queries in `basic_analysis.sql` for basic analysis.
   - Run the queries in `advanced_analysis.sql` for advanced analysis.

3. **Power BI Dashboard:**
   - Open the `airline_dashboard.pbix` file in Power BI Desktop.
   - Explore the visualizations and insights provided in the dashboard.
   - Alternatively, view the Power BI dashboard [here](https://drive.google.com/file/d/1IB6SLrczIdkNBNWgXkjWowxZDs_FXu8q/view?usp=sharing).

