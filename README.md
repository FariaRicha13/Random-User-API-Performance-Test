# Random-User-API-Performance-Test


## technlogies and tools used
- JMeter

## Scenario of this project
- For a given amount of requests in a given amount of time, calculate the throughput
- Perform load test by increasing the time, for the expected requests in that time (calculating the expected request = time * throughput) until the requests reaches 1/4 of the given requests amount.
- Perform stress test by keeping the time constant but increase the requests gradually from the expected requests until it reaches it stress point/ bottle neck ( a point where error will be <=1%).



## How to run this project
- Clone this project
- move the project to location\apache-jmeter-5.5\bin
```run ApracheJMeter.jar from the folder or om cmd prompt > Jmeter```
```open the project file```

## Pre-requisities
** You will need an API to test**

## URL/API for Test
https://random-data-api.com/api/v2/users

## Test Cases and Issues
https://docs.google.com/spreadsheets/d/1iKVEYWJFCEvpW8DAwPoKHFHPX-yPewQ43jnKxf3crRs/edit?usp=sharing

## OUTPUT


![LoadTest_1](https://user-images.githubusercontent.com/81919644/194106752-9375264c-e5a2-473b-b4ea-5ec76f885275.PNG)
![StressTest_1](https://user-images.githubusercontent.com/81919644/194106785-86338dac-216c-41e4-be7d-b1ee6e855349.PNG)
