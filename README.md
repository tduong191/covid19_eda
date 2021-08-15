# covid19_eda

This script is used to clean the raw data. It does the following things in this Rmd:

1. Rename and remove the columns so that it is consistent with the dictionary.
2. Remove all Vietnamese tones.
3. Recode country_infected, city_infected, flightInfo, and flightseatInfo columns
4. Fix all Dates columns
5. Derive the first positive test date - PCR1.pos

