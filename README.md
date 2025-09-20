# Seoul bike rental

A dataset of bike rental in Seoul, South Korea is provided and asked to find solution


## Scenario
Imagine you are a data professional consulting for the transportation department in Seoul, South Korea. Your client contact is the director of the department. For your next project, the director asks you to analyze the rented bicycle data they've gathered in 2018 in order to learn the best time of day to have their maintenance teams repair bikes. The director wants the maintenance work to occur during lower traffic times, when bicycle rental numbers are minimal, but still during standard working hours (8 a.m. to 5 p.m). 

Your task is to use Tableau to design a data visualization that illustrates the low-traffic times of standard workdays in order to remove bicycles from circulation for maintenance. The director wants the visualization to include gradients of orange to represent the company colors. Be sure your data visualization is clear, accessible, and ethical. 
[Tableau link](https://public.tableau.com/views/SeoulBikeRentals_17583818730700/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


## Data Exploration and Profiling
1. Open Tableau Public
2. Upload dataset .xls
1. Decide which columns are required for visualization
2. Check the data types for the applicable columns you selected

**DATA**
![alt image](https://github.com/MohTarique/Seoul-bike-rental-/blob/60709b5f0a9e54567df4c3e7d7db534f105460a7/images_tableau/mvi-WqE-RqOPXtqPnECeuA_c6db52bba96e495682d6f74b5185f5f1_ADA_SR-011-Data-Types-Seoul.png)

## Create Worksheet
build worksheet as shown in image and calculate feild
![alt image](https://github.com/MohTarique/Seoul-bike-rental-/blob/54ec802e665c65f3ace6df6dcb451fd979701f3f/images_tableau/Screenshot%20(106).png)

**Calculated Field** : as in this calculate feild captures the min hour in working days in all seasons
![alt image](https://github.com/MohTarique/Seoul-bike-rental-/blob/e533b0fa8670a9d4f96923dbdfff876cd8f69294/images_tableau/Screenshot%20(105).png)

here min hour for average bike rentals in 10 but with the help of calculted feild even if changes for every season and weekday it will capture minimun

## DASHBOARD
Finally the dashboard with filters for season 
![alt image](https://github.com/MohTarique/Seoul-bike-rental-/blob/e533b0fa8670a9d4f96923dbdfff876cd8f69294/images_tableau/Dashboard%201.png)

## CONCLUSION
HOUR = 10 AM 
is the right time with minimum traffic in bike rentals throughout the weekday and all seasons , so for servicing and repairs 10 AM is most appropriate

   
