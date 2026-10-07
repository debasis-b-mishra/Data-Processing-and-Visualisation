# Ford GoBike System Data Exploration
## by Debasis Mishra


## Dataset

> The Ford GoBike System Data dataset contains information about individual bike-sharing trips made in the San Francisco Bay Area during February 2019. Each record represents a single bike trip and includes details such as trip duration, start and end times, station locations, user type, rider gender, and birth year.

> The dataset was provided through the Udacity Data Visualization Project and originates from the Ford GoBike bike-sharing system.


## Summary of Findings

> The exploratory analysis identified several important patterns in rider behavior and bike-sharing usage.

## Trip Duration
Trip duration was heavily right-skewed.
Most trips were relatively short.
A small number of trips had extremely long durations.
A logarithmic transformation provided a clearer view of the distribution.

## Rider Demographics
> Most riders were between 25 and 40 years old.
Male riders represented the largest user group.
The service was primarily used by working-age adults.

## User Types 
> Subscribers accounted for the majority of trips.
Customers represented a much smaller portion of users.
Customers generally took longer trips than Subscribers.

## Time-Based Usage Patterns
> Trip activity peaked during morning and evening rush hours.
Bike usage was highest on weekdays.
Subscriber activity showed strong commuting patterns.

## Relationships Between Features
> User type had the strongest influence on trip duration.
Customers consistently took longer trips than Subscribers.
Age showed only a weak relationship with trip duration.
Subscribers were more active during weekdays, while Customers represented a larger share of weekend trips.


## Key Insights for Presentation

> The Ford GoBike system is primarily used by Subscribers for weekday commuting, while Customers tend to take longer, leisure-oriented trips, with overall usage peaking during morning and evening rush hours.