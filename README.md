# Budget-Tracker
This is an updated version of a budget tracker that adds offline functionality. 

![Screen Shot 2021-07-24 at 3 53 11 PM](https://user-images.githubusercontent.com/79954805/126882773-f7aac32a-d48e-4b3e-bd08-2013d09e84ef.png)
## Description 

This project updated the initial version of the budget tracker to include offline functionality. 

![Screen Shot 2021-07-24 at 3 58 41 PM](https://user-images.githubusercontent.com/79954805/126882878-5525afa1-b876-4f32-b939-75c8d13eb0f8.png)

### Website
https://peaceful-caverns-60951.herokuapp.com/

## Table of Contents
- [Installation](#installation)
- [Technologies](#technologies)
- [Usage](#usage)
- [Tests](#tests)
- [Contributions](#contributions)
- [Questions](#questions)

## Installation
You can find the application on the website provided ⬆️.

## Technologies
- Javascript
- node.js
- express.js
- Mongodb
- Mongoose
-Indexed db
-Mongo Atlas

## Usage
 To use this application navigate to the weblink.  At the top of the page you will see two input boxes. Type the label for the transaction you wish to enter, then the amount.  Click add or subtract funds and you will see the tranaction loaded below the entry boxes.  The balance at the top of the application will also change to reflect the new transaction.  If there is no internet connection, this application will still function properly by storing the information entered while offline and sending it when internet connectivity is restored.  
 
## Tests
To test that the application is functioning correctly, navigate to the application utilizing a google chrome browser.  Right-click on the page and click "inspect".  After clicking inspect, navigate to the network tab at the top of the page.  Find the dropdown that says "No Throtteling" and click the option that says "Offline".  This will allow the application to duplicate the experience of losing internet functionality.  Next, navigate to the application tab.  Find "storage" on the left side, find "indexed db", and finally navigate into the "budget" tab, and you should see "new_bud..", click there.  On the right side of the screen you should see a key value pair of columns.  Now, enter a new transaction and it will appear in the feilds on the right side. This confirms that the application is functioning correctly.  You may also notice an error in the console that says that the request failed.  This is perfect, because the application is offline.  When you return theapplication to "no throtteling" on the network tab, you should see a pop-up box that confirms that your offline entry has been submitted successfully. 

## Contributions
This application was created by Trilogy for the University of Arizona.  The developer has only added online functionality to this application. 

## Questions
If you have any questions or need additional information, you can reach me at the following places:
### Github
LindseyKrause
https://github.com/LindseyKrause
