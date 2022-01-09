# **NYC Citi Bike Analysis**

## *Overview*

After being inspired by the Citi Bike program in NYC, we are interested in creating a similar bikesharing program in Des Moines, IA. To begin our analysis, we will use data from NYC to learn how the program works there. 

We have a CSV file with all August 2019 Citi Bike data. It includes a record of 2,344,224 total trips. It's good for looking at summertime trends, but less useful helping us predict winter riding behavior.

## *Results*

Link to [Tableau Story](https://public.tableau.com/views/NYCCitibike_16417158579650/citibikeStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link).

There are 8 visualizations in the Story:

	- Top Starting Locations
		* Starting locations are concentrated in Manhattan, especially in the Upper West Side and down to Soho.

	- Top Ending Locations
		* Ending locations are similar to starting locations, so the bikes are not moving too far.

	- Peak Hours, August
		* Busiest hours are 8:00am and 6:00pm, so it's likely that many are using the bikes to commute to and from work.

	- Trips by Weekday per Hour
		* Like the peak hour visualization, this heat map shows heavy use during weekday rush hour commute. At the same time, it reflects different behavior on Saturday/Sunday, with the most rides from 10:00am to 1:00pm.

	- Trips by Gender, Weekday per Hour
		* Again, this demonstrates greatest usage during the weekday commute, but by breaking down by gender, we can see that men use the service more frequently than women.

	- Trips by Gender by Weekday
		* This visualization also shows men using the service more than women. Thursday and Friday are the busiest days.

	- Checkout Times
		* Nearly all bikes are checked out for less than one hour, and the vast majority are checked out for less than 30 minutes.

	- Checkout Times by Gender
		* All genders use the bikes for a similar duration; however, men use the service nearly 3 times more frequently than women do.

## *Summary*


As we consider applying this model to Des Moines, more work will need to be done to draw good comparisons. For example, it would be helpful to compare weather data to trip data using a line chart. Also, after seeing the difference in ridership among genders, we should start with a horizontal bar visualization showing total rides by gender. 

It's reassuring that bikes are dropped off in roughly the same areas where they are picked up, so there should not be a need to move them back to a starting position after each ride. Also, it's encouraging that the data points to a core user group of residents/commuters. They may be more willing to use the service in December or January than a tourist would. Moreover, NYC hosts a lot more tourists than Des Moines, so to the extent that we are looking at tourist behavior, it may not translate to Iowa.


