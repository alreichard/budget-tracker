# budget-tracker

## Information 
In this application, I took a fully functioning online budget tracking application and gave it offline capablities. It takes in a note with an amount of money that is either added or subtracted from your budget, and saves it to a database. It did not, however, do so when wifi or cellular data is turned off. This application helped me learn how to cache code, along with save locally to something other than locsl storage/ by using the indexedDb, I was able to save it with the same functionality as online. When the wifi restarts, it saves the local database to the mongo db, and clears the locally stored version. 

## Application access

## How to use
This application is very simple. You can add or subtract a budget by butting in the amount and pressing add or subtract.