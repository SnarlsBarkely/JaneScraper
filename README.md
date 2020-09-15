# JaneScraper
A simple webscraper for products on iheartjane. This program takes in a iheartjane store id, and outputs all of the items into a text file at the specified output path.

# REQUIREMENTS
Java: https://www.java.com/ES/download/ (Java 1.7+ required)

# Finding Store ID's
You can find your dispensary's jane id by going to any page within the store and clicking F12 (you may need to hold the FN key as well as F12), and then pasting the following in: iheartjane.com/v1/stores/

You should see a link similar to this one: https://api.iheartjane.com/v1/stores/!!!!/embed.js  
The !!!! will be an actual number and this is what you will need to type into the window that pops up when you click on the JaneScraper.bat file. 

You will also need to select where the items will be printed to. The items are printed to a text file at the path specified in the "output path" on the form


# Running
Click the file called Janescraper.exe after installing java and it should bring up a form asking for a store ID and output path, as well as a 'Get Scrapin!' button. Find your store ID using the instructions above, and select where you want the products printed to. The output is a text file with each item on a line. 
