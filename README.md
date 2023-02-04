# Airport-Traffic-ETL-and-Viz-

Airport Traffic by US and International Carriers

Business Case
As a research and analytics team at an international carrier, we need to create data pipelines to produce reports using publicly available U.S. Department of Transportation (USDOT) airport traffic data. Airline executives have been consuming this information indirectly through USDOT reports and additional assets produced by business analysts.

Our mandate is to create a data pipeline that drives a reporting system on international flights. The reporting system, including changes to the data pipeline, will be maintained by business analysts with help from the analytics team. Analysts often work on such pipelines that take larger datasets and shrink them into smaller dimensions. The goal of our team is to help them do so faster, more efficiently and in a reproducible manner.

The data comes from the U.S. International Air Passenger and Freight Statistics Report. As part of the T-100 program, USDOT receives traffic reports of US and international airlines operating to and from US airports. Data engineers on the team ingest this publicly available data and provide us with the following datasets:

departures: Data on all flights between US gateways and non-US gateways, irrespective of origin and destination.
Each observation provides information on a specific airline for a pair of airports, one in the US and the other outside. Three main columns record the number of flights: Scheduled, Charter and Total.
passengers: Data on the total number of passengers for each month and year between a pair of airports, as serviced by a particular airline.
The number is also broken down by those in scheduled flights plus those in chartered flights.
We will start with data for 2017.

Click Below for Viz:

https://public.tableau.com/app/profile/abdul.khaliq/viz/AirportTraffic_16755323424630/AirportTrafficbyUSandInternationalCarriers?publish=yes
