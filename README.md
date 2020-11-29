# Analysis-of-Airline-Data
# Analysis of Airport Data using Hadoop-Hive

# PROBLEM STATMENTS:
A.Find list of Airports operating in the Country India
B.Find the list of Airlines having zero stops
C.List of Airlines operating with code share
D.Which country (or) territory having highest Airports
E.Find the list of Active Airlines in United state


# Data Description
In this use case there are 3 data sets. Final_airlines, routes.dat, airports_mod.dat


# Air Ports data set i.e airports_mod.dat
It contains the following fields

Airport ID Unique OpenFlights identifier for this airport.

Name Name of airport. May or may not contain the City name.

City Main city served by airport. May be spelled differently from Name.

Country Country or territory where airport is located.

IATA/FAA 3-letter FAA code, for airports located in Country "United States of America".

3-letter IATA code, for all other airports.

Blank if not assigned.

ICAO 4-letter ICAO code.

Blank if not assigned.

Latitude Decimal degrees, usually to six significant digits. Negative is South, positive is North.

Longitude Decimal degrees, usually to six significant digits. Negative is West, positive is East.

Altitude In feet.

Timezone Hours offset from UTC. Fractional hours are expressed as decimals, eg. India is 5.5.

DST Daylight savings time. One of E (Europe), A (US/Canada), S (South America), O (Australia), Z (New Zealand), N (None) or U (Unknown). See also: Help: Time

Tz database time Timezone in "tz" (Olson) format, eg. "America/Los_Angeles". zone
