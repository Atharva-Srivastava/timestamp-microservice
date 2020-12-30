
# Timestamp Microservice

Steps to run this repository:-
- Clone this repository from Github
- In your Code Editor or IDE run "npm install" 

Features of this API:-

A request to the API by /api/timestamp/:date? with a valid date will return a JSON object with a unix key that is a Unix timestamp of the input date in milliseconds

A request to the API by /api/timestamp/:date? with a valid date will return a JSON object with a utc key that is a string of the input date in the format: Thu, 01 Jan 1970 00:00:00 GMT

An empty date parameter will return the current time in a JSON object with a unix as well as utc key

The API handle dates that can be successfully parsed by new Date(date_string)

