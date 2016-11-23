# Front End Test
An AngularJS focused take home test for Front-end Developers.

## Instructions
+ Clone this repo
+ Complete this exercise and submit either a zip of the solution or a link to a new repo
+ Please incorporate the included `angular.min.js` (Angular 1.5.8) framework into your solution. All other choices of libraries, frameworks, etc. are up to you.

## Requirements
+ Solution should be responsive
+ Using the included `weather.json` file, show the "current" conditions for New York. This should include:
  + Location (ie. New York, NY, USA)
  + Current weather description (ie. sunny)
  + Current temperature
  + Today's high temperature
  + Today's low temperature
+ Allow the user to toggle more data in the current conditions area:
    + Wind Speed
    + Humidity
    + Pressure
    + Sunrise/Sunset Time
+ Show the 7 Day forecast as a multi-line chart (charting library is up to you but should be incorporated as an Angular Directive.)
  + Y axis should show the High and Low temperature as separate lines
  + X axis should show 7 days (including the "current" day)
  + The chart should have a tool tip that when activated shows:
    + Day of the week
    + High temperature
    + Low temperature
    + Weather description (ie. Breezy)
+ __Bonus:__ Was this too easy? Want to make it a real app? Use the Yahoo weather API https://developer.yahoo.com/weather/ or Open Weather API https://openweathermap.org/api defaulted to New York, NY, but allow the user to change the location by Zipcode.
