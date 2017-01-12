Web App Programming Challenge
=============================

Use either Python or JavaScript (Python ([Flask](http://flask.pocoo.org), [Django](http://djangoproject.com)) / JavaScript ([Node](https://nodejs.org/))) to create a backend, and a JavaScript framework/library ([Angular](https://angularjs.org/), [Angular 2](https://angular.io/), [React](https://facebook.github.io/react/), etc) on the frontend, create a standalone RESTful web application which loads data from the CSV files (located in the data directory of this repository) and plots three lines (one for each stock symbol) onto a chart using the charting library of your choice. The y-axis of the chart should be the "Close" price field, the x-axis should be the "Date" field.

Your code will be assessed on quality, style, readability, and documentation. Please include a brief description of how you went about accomplishing the task and any hurdles you might have faced. In the description, be sure to also include instructions for running the app. Final deliverable should be compressed and e-mailed back to us.

If you're not sure which charting library to use, you could research one or more of the following libraries:

- [Dygraphs](http://dygraphs.com)
- [c3.js](http://c3js.org)
- [d3.js](http://d3js.org)
- [Highcharts](http://www.highcharts.com/)
- [Google charts](https://developers.google.com/chart)

Bonus points
------------
- Calculate and plot a moving average on top of the price
- Angular 2 & TypeScript on the frontend
- Allow interactive toggling between multiple stocks
- Allow interactive date selection and/or zooming of x-axis
- Load the CSV files into a sqlite database to be used directly by the web app
