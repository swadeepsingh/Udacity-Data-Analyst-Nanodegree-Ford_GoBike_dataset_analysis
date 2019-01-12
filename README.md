# Ford GoBike Trip Data Analysis

In this part of project, our goal is to conduct an exploratory data analysis on Ford GoBike Trip dataset. We will use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part is structured, going from simple univariate relationships up through multivariate relationships, but it does not need to be clean or perfect. This part of the project is gives opportunity to ask questions on data and make discoveries.


# Table of Contents:

    Introduction
    Exploratory data analysis
    Explanatory data analysis
    Conclusions


# Introduction:

The Ford GoBike Trip dataset includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay & nearby areas. Each trip is anonymized and includes:

    Trip Duration (seconds)
    Start Time and Date
    End Time and Date
    Start Station ID
    Start Station Name
    Start Station Latitude
    Start Station Longitude
    End Station ID
    End Station Name
    End Station Latitude
    End Station Longitude
    Bike ID
    User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
    Member Year of Birth
    Member Gender


# Exploratory data analysis:

# Observations:

    1. Columns names are consistent (lower snakecase)
    2. Generate minutes for trip duration from duration_sec 
    3. Stripping time from the start_time & end_time column will make the dataset easier to work with 
    4. Calculate the distance for trip using geo location data
    5. Filter data to include reasonable member age range from member_year_of_birth
    6. Create bins for member age group

# Questions: 

    Question 1: How fast the Ford GoBike is growing?
    Question 2: How does rides trend vary per age, gender, weekday, and hour of a day?
    Question 3: How does subscribers and customers behave differently?
    Question 4: Which docks are used more frequently?
    Question 5: When and where bike share for all rides happened ?


# Explanatory data analysis:

1. 20-30 age group users are rapidly using bikes as compared to other user groups
2. 20 to 40 years old people took the more than 70% of bike rides. Among those, 20 to 30 years old people's rides account for around 40% of all bike rides.
3. Male took 76% of all bike rides, and female took 22% of them.
4. Majority of people uses Ford Gobike on weekdays. And reduced to half on weekends.
5. Majority number of people uses this service during commute time. 8am and 5pm are the peak hours for this service. Also, few people uses it more during lunch time.
6. 88.92% of bike rides are from subscribers.
7. The fluctuations in Subscriber profile is because of weekends.
8. Average trip duration for Subscriber is 10.769067 and for Customer is 23.846594.
9. Interestingly, both subscribers and customers trip distance were almost same.
10. 20-30 age group riders are more in both user type.
11. San Francisco Caltrain Station 2 (Townsend St at 4th St) is the top station where Ford Gobike trip starts and ends.
12. 5pm is peak hour for 'Bike share for all' rides
13. Most bike share for trip starts at 5th St. at Virginia St.

