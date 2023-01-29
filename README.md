# estructures_Dataframe
S3 T02: what are the causes for the delays of these flights?

In order to answer this question, we are going to analyze the provided dataset, containing up to 1.936.758 different internal flights in the US for 2008 and their causes for delay, diversion and cancellation; if any.
The data comes from the U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics (BTS).
This dataset is composed by the following variables:

    Year 2008
    Month 1-12
    DayofMonth 1-31
    DayOfWeek 1 (Monday) - 7 (Sunday)
    DepTime actual departure time (local, hhmm)
    CRSDepTime scheduled departure time (local, hhmm)
    ArrTime actual arrival time (local, hhmm)
    CRSArrTime scheduled arrival time (local, hhmm)
    UniqueCarrier unique carrier code
    FlightNum flight number
    TailNum plane tail number: aircraft registration, unique aircraft identifier
    ActualElapsedTime in minutes
    CRSElapsedTime in minutes
    AirTime in minutes
    ArrDelay arrival delay, in minutes: A flight is counted as "on time" if it operated less than 15 minutes later the scheduled time shown in the carriers' Computerized Reservations Systems (CRS).
    DepDelay departure delay, in minutes
    Origin origin IATA airport code
    Dest destination IATA airport code
    Distance in miles
    TaxiIn taxi in time, in minutes
    TaxiOut taxi out time in minutes
    Cancelled *was the flight cancelled
    CancellationCode reason for cancellation (A = carrier, B = weather, C = NAS, D = security)
    Diverted 1 = yes, 0 = no
    CarrierDelay in minutes: Carrier delay is within the control of the air carrier. Examples of occurrences that may determine carrier delay are: aircraft cleaning, aircraft damage, awaiting the arrival of connecting passengers or crew, baggage, bird strike, cargo loading, catering, computer, outage-carrier equipment, crew legality (pilot or attendant rest), damage by hazardous goods, engineering inspection, fueling, handling disabled passengers, late crew, lavatory servicing, maintenance, oversales, potable water servicing, removal of unruly passenger, slow boarding or seating, stowing carry-on baggage, weight and balance delays.
    WeatherDelay in minutes: Weather delay is caused by extreme or hazardous weather conditions that are forecasted or manifest themselves on point of departure, enroute, or on point of arrival.
    NASDelay in minutes: Delay that is within the control of the National Airspace System (NAS) may include: non-extreme weather conditions, airport operations, heavy traffic volume, air traffic control, etc.
    SecurityDelay in minutes: Security delay is caused by evacuation of a terminal or concourse, re-boarding of aircraft because of security breach, inoperative screening equipment and/or long lines in excess of 29 minutes at screening areas.
    LateAircraftDelay in minutes: Arrival delay at an airport due to the late arrival of the same aircraft at a previous airport. The ripple effect of an earlier delay at downstream airports is referred to as delay propagation.

Source: __[kaggle](https://www.kaggle.com/datasets/giovamata/airlinedelaycauses)__
