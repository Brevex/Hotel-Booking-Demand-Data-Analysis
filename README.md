<h1 align = "center"> Hotel Booking Demand Data Analysis </h1><br>

<h2> &#128269; About the project </h2><br>

<p>A data analysis in Python of demand for urban hotels and resorts showing their causes and relationships.
The analysis makes a comparison of hotel types in Portugal, showing periods with higher
demand, number of canceled reservations and origin of customers</p><br>

<h2> &#128302; Technologies Used </h2><br>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py" />
  </a>
</p>

<br><h2> &#128202; Analysis Result </h2><br>

<details>
	<summary>database columns</summary><br>
	
  	01 : hotel
	02 : is_canceled
	03 : lead_time
	04 : arrival_date_year
	05 : arrival_date_month
	06 : arrival_date_week_number
	07 : arrival_date_day_of_month
	08 : stays_in_weekend_nights
	09 : stays_in_week_nights
	10 : adults
	11 : children
	12 : babies
	13 : meal
	14 : country
	15 : market_segment
	16 : distribution_channel
	17 : is_repeated_guest
	18 : previous_cancellations
	19 : previous_bookings_not_canceled
	20 : reserved_room_type
	21 : assigned_room_type
	22 : booking_changes
	23 : deposit_type
	24 : agent
	25 : company
	26 : days_in_waiting_list
	27 : customer_type
	28 : adr
	29 : required_car_parking_spaces
	30 : total_of_special_requests
	31 : reservation_status
	32 : reservation_status_date
</details>

<details>
	<summary>missing values percentage</summary><br>
	<p>After importing the data, missing values were identified in some columns</p>
	
  	children: 0.003% 
	country: 0.409% 
	agent: 13.686% 
	company: 94.307%
</details>

<details>
	<summary>null values</summary><br>
	<p>Number of null values per column</p>
	
  	children: 4
	country: 488
</details>

<details>
	<summary>booking percentage</summary><br>
	<p>Booking percentage by hotel type</p>
 	<img src="https://github.com/Brevex/Hotel-Booking-Demand-Data-Analysis/blob/73f28799915b4907a54496bf01a4c79b8b4c743e/readme%20images/booking%20percentage.png">
</details>

<details>
	<summary>comparison between canceled and non-cancelled bookings</summary><br>
	<p>Comparison between the number of canceled and non-cancelled reservations in each type of hotel</p>
 	<img src="https://github.com/Brevex/Hotel-Booking-Demand-Data-Analysis/blob/73f28799915b4907a54496bf01a4c79b8b4c743e/readme%20images/cancelled%20bookings%20comparison.png">
</details>

<details>
	<summary>annual evolution of bookings</summary><br>
	<p>Evolution of the number of reservations between 2015 and 2017. Note that only the year 2016 has data for all months</p>
 	<img src="https://github.com/Brevex/Hotel-Booking-Demand-Data-Analysis/blob/73f28799915b4907a54496bf01a4c79b8b4c743e/readme%20images/annual%20bookings.png">
</details>

<details>
	<summary>customers origin</summary><br>
	<p>List of the 10 countries where the most customers come from. Note that Portugal is 1st because the hotels in the database are in Portugal.</p>

  	1	PRT	21071
	2	GBR	9676
	3	FRA	8481
	4	ESP	6391
	5	DEU	6069
	6	IRL	2543
	7	ITA	2433
	8	BEL	1868
	9	NLD	1717
	10	USA	1596
</details>

<details>
	<summary>months with more demand</summary><br>
	<img src="https://github.com/Brevex/Hotel-Booking-Demand-Data-Analysis/blob/73f28799915b4907a54496bf01a4c79b8b4c743e/readme%20images/busiest%20months.png">
</details>

<details>
	<summary>period of highest price</summary><br>
	<p>Months when prices are higher. Note that demand for resorts increases significantly during the European summer, making the price increase.</p>
	<img src="https://github.com/Brevex/Hotel-Booking-Demand-Data-Analysis/blob/73f28799915b4907a54496bf01a4c79b8b4c743e/readme%20images/price%20per%20month.png">
</details>

<details>
	<summary>average cancellation per month</summary><br>
	<p>average number of bookings canceled per month. Note that it is understandable that the months with the highest demand are the ones with the most cancellations.</p>
	<img src="https://github.com/Brevex/Hotel-Booking-Demand-Data-Analysis/blob/73f28799915b4907a54496bf01a4c79b8b4c743e/readme%20images/average%20cancellation.png">
</details>

<details>
	<summary>heatmap</summary><br>
	<p>heat map that aims to relate causes and relationships of certain values in the database.</p>
	<img src="https://github.com/Brevex/Hotel-Booking-Demand-Data-Analysis/blob/2f5ff87f4032fc4d1483167686796d6aca870696/readme%20images/heatmap.png">
</details>

<br><h3 align = "center"> - By <a href = "https://www.linkedin.com/in/breno-barbosa-de-oliveira-810866275/" target = "_blank">Breno</a> - </h3>
