## Scrape FX ##

1. For each forex news service (forexfactory, investing.com etc)
2. If we don't have a store of the calendar, get a schedule for the next (x months)
3. Set a timer to sleep and wait for 2 minutes before the time of release.
4. At that time, get the data over and over until it changes.
5. Fire an event with the information
6. Console service gets and reports result to console
7. Detect what needs to run next


The end result for now would be a console app that just streams the indicators one line at a time
Time: 03/07/2021 15:30:09, Source:ForexFactor, Name: NFP: Forecast: 500k, RESULT: 543k  
Time: 03/07/2021 15:30:11, Source:DailyFx, Name: NFP: Forecast: 500k, RESULT: 543k  
