# Bike Sharing usage by Casual Riders and Subscribers

### By Anorup Kanti Das

<br>

## About The Analysis
The goal for this analysis is to determine the usage difference of bike sharing by Cyclistic among Member & Casual, and find out if there is way Cyclistic can advertise to Casual customers to switch to becoming a Member becuase more profit comes from Members.

### About The Data
The data has been sourced from Cyclistic’s data warehouse. The data contains details about Bike Sharing usage in the last five quarters. You can download the data from [here](https://divvy-tripdata.s3.amazonaws.com/index.html).

## Tools Used

* **R**

## Analysis

<img src= "">

### It seems like the number of rides are mostly covered by subscribers on weekdays. Indicating commuting to work.

<br>
<br>

<img src= "">

### Interesting. Average Ride Duration is almost same everyday for Subscribers, and is very low. Again indicating commuting to work. On the other hand, Average Ride Duration for Casual Riders are long, indicating tourists or recreational riders.

<br>
<br>

<img src= "">

### The density plots below shows the same insights as the previous graph chart. Indicating that more subscriber riders ride for less time and casual riders ride for longer.

<br>
<br>

<img src="">
### This plot shows that the number of rides increases in summer for both rider types and falls in winter.

<br>
<br>

## Key Findings

* **Ride Frequency**: Members consistently make more rides than Casual users, especially on weekdays. This suggests members are largely commuters.

* **Ride Duration**: Casual riders take significantly longer trips than Members. This aligns with patterns of tourists and recreational riders.

* **Weekly Trends**: Casual usage spikes on weekends, while Member usage is higher during weekdays, again pointing to commuting behavior.

* **Ride Distribution**: The density plot shows Casual rides have a wider spread and heavier tail, confirming they sometimes take very long trips compared to Members.


## Business Insights

1. **Casual = Tourists / Leisure**

  + Longer rides, weekend peaks.

  + Likely renting bikes for sightseeing, group trips, or one-off leisure activities.

2. **Members = Commuters / Daily Users**

  + Shorter, frequent weekday rides.

  + Likely using bikes as part of their regular work commute.

## Recommendations

1. **Membership Conversions**

  + Create targeted campaigns for Casual users offering “Weekend-to-Membership” discounts. Example: *“Save more when you ride regularly, convert to a Member today!”*

  + Offer multi-day tourist passes that subtly encourage upgrading to full membership.

2. **Commuter Incentives**

  + Partner with employers for corporate membership discounts.

  + Highlight time savings and cost-effectiveness vs. other transport.

3. **Seasonality & Events**

  + Launch seasonal promotions (summer = more tourists, winter = more locals).

  + Target event-based traffic (festivals, conferences) with special deals.

<br>
<br>

## Key Performance Indicators

### Total Rides by Rider Type

<table>
    <tr>
        <th>User Type</th>
        <th>Total Rides</th>
    </tr>
    <tr>
        <td>Casual</td>
        <td>925345</td>
    </tr>
    <tr>
        <td>Subscriber</td>
        <td>3315766</td>
    </tr>
</table>

<br>

### Average Ride Length by Rider Type

<table>
    <tr>
        <th>User Type</th>
        <th>Average Ride Length</th>
    </tr>
    <tr>
        <td>Casual</td>
        <td>3556.8495 secs</td>
    </tr>
    <tr>
        <td>Subscriber</td>
        <td>848.3654 secs	</td>
    </tr>
</table>

<br>

### Percentage of Riders

<table>
    <tr>
        <th>User Type</th>
        <th>Percentage</th>
    </tr>
    <tr>
        <td>Casual</td>
        <td>21.28%</td>
    </tr>
    <tr>
        <td>Subscriber</td>
        <td>78.18%</td>
    </tr>
</table>
