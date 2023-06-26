# JPMC Task 2
Use JP Morgan Chase's frameworks and tools Implement JP Morgan Chase’s Perspective open source code in preparation for data visualization

# Aim: 
Take an incomplete setup of Perspective, i.e. a graph that updates manually, and make it work with the code from Task 1 such that it now updates automatically by continuously requesting from the server application

[goal-a] In the client application, observe that when new data feed is retrieved whenever you click the 'Start Streaming Data' button, the previous entry is re-entered into the table. Update the application so that the table does not have duplicated entries.

[goal-b] We also want the react app to keep continuosly requesting data from the python server. Currently, the data feed is called only once every time the 'Start Streaming' button is clicked. Change the application to continuously query the datafeed every 100ms when the 'Start Streaming' is clicked.

[goal-c] Currently, the Perspective element only shows the data in table view after the data loads. Add Perspective configurations so that when the data is loaded, it shows the historical data of ask_price ABC in the Y line chart.

# Recommended versions:
node v11.0.0 and npm v6.4.1

Open http://localhost:3000 to view the app in the browser.

# Known Issues:
Some users seem to be having trouble with the unzipped version of the node_modules back up for windows. This is the alternative unzipped version: https://drive.google.com/drive/folders/1wzIlt-OeiK6nYEHidsOGlpJ_KmeoPVXz
Note: You may need to (hard) refresh the link to the public gdrive to see all of the files/folders e.g. @jpmorganchase/perspective as it takes gdrive a bit to load them for you.

# How to fix the code to meet the objectives:
To make the changes necessary to complete the objectives of this task, follow this guide(https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/making_changes_m2_v2.pdf).
