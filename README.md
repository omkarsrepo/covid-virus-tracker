# COVID-19 Virus Tracker

## Based on:
- Java 11
- Spring Boot
- Thymeleaf
- [CSSEGISandData CSV Covid-19 Data](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv)

### Run and launch on [http://localhost:8073/](http://localhost:8073/)
![Application Image](https://i.vgy.me/wzT73p.png)

### Description:
Application fetches data using an online [CSV data file](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv) using `@Scheduled(cron = "0 0 * * * *")` cron job that runs every hour and fetches the fields from the file which are later displayed on the `home.html` page using Thymeleaf framework.

## Thank you for reading this!