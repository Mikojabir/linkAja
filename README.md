# linkAja_
Repository technical test for linkAja

How to run and create report:

1. Download and install Node.js package
In a web browser, navigate to https://nodejs.org/en/download/

2. install Newman Report:
npm install -g newman-reporter-htmlextra

3. clone repository:
https://github.com/Mikojabir/linkAja.git

4. go to file into "Linkaja.postman_collection.json" 
- if you can run only postman, import collection into your postman and after importing, run collection.
- if you run and create reporting, Run script for created report:
newman run Linkaja.postman_collection.json -r htmlextra --reporter-htmlextra-export linkaja.html --reporter-htmlextra-title "Report API Linkaja"
