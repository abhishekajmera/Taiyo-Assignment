# Taiyo-Assignment

The problem statement was to code a harvester using python to harvest brownfield data from a public source.

I scraped data from the following website:
https://www.grid.ac/institutes

Starting from the first Explore page, I used Selenium to get the URLs of the individual institute webpages (40 pages in total).
![Explore_page](https://user-images.githubusercontent.com/37187598/126042396-d08f3cd3-5ef3-4bac-b961-c2572770dca7.PNG)

I then used BeautifulSoup to loop over each of the webpages using the URLs gathered, and scrape the parameters.

![nsfe](https://user-images.githubusercontent.com/37187598/126042513-c24199f3-6bda-4e83-9127-734d5341e65f.PNG)

 I appended information from each of the webpages to an array and converted it to a dataframe. 
 
 Paramters scraped:
 
1) Institute Name - The name typically used to refer to the institute.
2) Grid_id - A unique ID for the institute
3) Type -	A list of types describing the institute eg: educational
4) Established - The year the institute opened, CE
5) Institute_link - link to the homepage for the institute
6) Wikipedia_link - 
7) Alias_lists -	A list of other names the institute is known as
8) City	- The name of the city
9) Country	- The name of the country
10) Country_geoNames_code	- The ISO 3166-1 alpha-2 code of the country
11) country_geoNames_id	-	The GeoNames ID of the country
12) City_geoNames_Code	- The ISO 3166-1 alpha-2 code of the city
13) city_geoNames_id - he GeoNames ID of the city
14) NUTS1_name - 	The NUTS level 1 region the GeoNames city is in
15) NUTS2_name - 	The NUTS level 2 region the GeoNames city is in
16) NUTS3_name - 	The NUTS level 3 region the GeoNames city is in
17) NUTS1_code
18) NUTS2_code
19) NUTS3_code









