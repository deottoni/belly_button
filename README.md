# Belly Button Biodiversity


In this assignment, I've built an interactive dashboard to explore the [Belly Button Biodiversity DataSet](http://robdunnlab.com/projects/belly-button-biodiversity/).
- - -


## Technologies 
* JavaScript
* Plotly.js
* html
* Python
* Flask
* Sqlite
* Heroku
- - -


## Step 1 - Plotly.js 

Use Plotly.js to build interactive charts for the dashboard. 

* PIE chart that uses data from your samples route (`/samples/<sample>`) to display the top 10 samples.

  ![PIE Chart](Images/pie_chart.png)

* Created a Bubble Chart that uses data from your samples route (`/samples/<sample>`) to display each sample.

  ![Bubble Chart](Images/bubble_chart.png)

* Display the sample metadata from the route `/metadata/<sample>` in the page.

* Update all of the plots any time that a new sample is selected.

- - -


## Step 2 - Flask API

Used Flask API starter code to serve the data needed for your plots.
- - -


## Step 3 - Heroku

Deploy the Flask app to Heroku.

Use the provided sqlite file for the database.

