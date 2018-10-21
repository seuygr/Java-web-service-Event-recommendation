# Mars - a Java webservice for Event Recommendation
The web page is designed for user to search events and purchase tickets. Users can also receive recommendations based on their search history and favorite events.

## Front-end development
The website is built by HTML, CSS and JavaScript based on AJAX.

## Back-end techinques
Apache Tomcat is used for local hosting and the data about the users(username, password, last login date, favorite history, etc.) is stored by MySQL.

## Deployment on EC2 and JMeter testing
In order to check the scalibility of the website, I uploaded the project onto Amazon EC2 and used JMeter to test its QPS. It turned out that the website can handle 200+ query per second.

## The final website page can be viewed at:
http://54.219.191.154/Mars/
login username: 1111
password: 2222

## TODO List
- Registration
- Recommendation based on machine learning algorithms
- Other events recommendation(Attraction) according to TicketMaster API
