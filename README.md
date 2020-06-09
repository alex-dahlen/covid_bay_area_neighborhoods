# covid_bay_area_neighborhoods

What neihbordhoods in the Bay Area are most affected by the coronavirus pandemic?

This project uses US census data to try to answer that question.  The full writeup is available here:

I compiled data about the prevalence of coronavirus at the zip code level into an excel spreadsheet called cases_per_zip.xlsx.
The data is copied from several counties board of health websites, and the data was collected on May 14.

The ipython notebook has all the code for this analysis.  It pulls US census data at the census tract level, 
rolls it up to the zip code level, and runs a correlation.  There's also code that plots heatmaps (chloropleths)
of the census data included at the end.
