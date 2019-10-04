# Map-Reduce-Program-in-Mongodb

Step 1: install Mongodb in our system (Windows or Linux)
Step 2: type the command mongo in the command prompt it will take u to the mongo shell
Step 3: create account Database using command: use account
   then it is switched to the account database
Step 4: open the New terminal do not go to mongo shell be local only type this command to import the csv file into your collection
->mongoimport --db account --collection detailscustomer --ignoreBlanks --type csv --headerline --file details.csv
 Here your detailscustomer is your coolection on the account database
 
 Step 5:Now to the mongo shell type show collections , it is show your collection that is imported then
 type the Map reduce that is there Command.txt file
 Step 6: Output is created in the 'Result4' COllection u can see this using command: db.Result4.find()
 it show the output.




