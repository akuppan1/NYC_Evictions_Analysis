# NYC_Evictions_Analysis

I was going through NYC’s OpenData and stumbled upon the evictions database.
<br>The dataset I used is: https://data.cityofnewyork.us/City-Government/Evictions/6z8x-wfk4
<br>The questions I wanted answered were:
1) How many evictions occurred in each borough each year?
2) How many evictions happened per year?
3) How had COVID-19 affected evictions in NYC?
4) Why did evictions occur even with a moratorium?
Without further ado, here is what I found:

Even with a moratorium, evictions still occurred in 2021.

We see there is a significant dip during COVID-19, however there is still eviction activity.

The number of evictions hovered around 20,000 and then we see the effects of the COVID-19 moratorium.

These are the top 10 zip codes and their eviction numbers for the years 2017–2019

These are the top 10 zip codes and their eviction numbers for the years 2020–2021
To answer my last question on why these evictions occurred in 2021. They may be due to special non-rent related circumstances. There are court cases related to each of those evictions. Another interesting note is the top 10 zip codes with the highest evictions changed dramatically after the moratorium.
________________________________________________________________________________________________________________________________________</br>

2022 Evictions Revisited - Tableau Edition!</br></br>
A while back I checked out what happened with evictions in NYC and what the future holds. As of January, the eviction moratorium has ended. I found much better tools to visualize the data. Tableau was fun. However, I already pushed it to the limits on the first day. I have a strange feeling it does not like to handle millions of datapoints.</br></br>
A quick pros and cons list of Tableau:</br>
PROS:</br></br>
1. It has excellent automated tools which can probably solve 90% of business needs when it comes to data monitoring, data analysis, creating daily dashboards for someone in management to look at</br>
2. Lots of integrations, easy to create "stories" with the data</br>
3. Very easy to learn and use out of the box.</br>
4. Awesome and colorful templates for data dashboard creation</br>
5. Making a plot on a map was so easy.</br></br>
CONS:</br></br>
I wanted to do some very specific things with the data. One of them was to figure out: How many cases were there per year and which year's cases were being handled currently? I tried many ways to filter the data on Tableau but I could not get it to group by a certain digit order for a row value. The fix here is to go down to the data level and create a new column in the data where I create specifically the column values or make a for loop where I can isolate the year value in each case number.
</br></br>The sheets and workbooks were reminiscent of Excel. However, I had issues printing my Tableau views. I found workarounds but there are problems that exist with this app.
</br></br>$70 per month to afford it…..whew! I wonder how good the open source plotting software is. Shoutout to Facebook Prophet!</br></br>

Now, we take a look at what evictions look like so far in March 2022 and what I found using Tableau.</br>
The data I used: https://data.cityofnewyork.us/City-Government/Evictions/6z8x-wfk4</br></br>
![image](https://user-images.githubusercontent.com/62908910/159192654-5200ed98-c8ab-4c88-a637-9e0723387428.png)</br>
![image](https://user-images.githubusercontent.com/62908910/159192665-54f7d2e6-fb78-4ca4-9f3a-b4ffe3b83970.png)</br>


So for this time around I want to narrow in on what the changes were 2021 to 2022.</br>
![image](https://user-images.githubusercontent.com/62908910/159192670-bccca061-4fe8-4b3f-94b9-ff8cd79ccf91.png)</br>

Overall observations are that 2022 evictions are spiking more than 200% per month compared to December 2021. However these numbers are still nothing compared to pre-COVID levels.</br>
2021 evictions reviewed again. We see the spike in December 2021 up to 73 evictions.</br>


However, those numbers pale in comparison to what is going on in 2022!We see this chart from Tableau that there are very few compared to pre-2020 levels</br>
![image](https://user-images.githubusercontent.com/62908910/159192691-e7d3262e-2b33-406d-b9fb-750257489e03.png)</br>
![image](https://user-images.githubusercontent.com/62908910/159192700-f717b20e-c28c-4b16-9a1e-691b9de1c7ec.png)</br>

Evictions per year per borough. Still the numbers are low. But for Queens, Bronx and Brooklyn the numbers have spiked considerably.We see here the per year totals for evictions, we are only 3 months into 2022 and we are nearly at double the evictions than ALL OF 2021 COMBINED.</br>

![image](https://user-images.githubusercontent.com/62908910/159192706-f2a300a8-c512-46c5-83bb-742c762f9e8f.png)</br>

We see the increase in density of points all over in 2022Based on the numbers from January 2022 to March 2022, the average is about 150 per month or 1,800 evictions by the end of 2022. Only time will tell what is in store.</br></br>
Future Work:</br></br>
Create an automated flow to update this data</br>
Figure out number of cases per year which are being handled. I want to know what is the status of all the new cases.</br>
