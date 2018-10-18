# Winter is coming

Build an app to feed the children of Winterfell

Fork and clone this repository
Please create your own html and js files

## STEP 1: Create your server!

All of the data is stored in the db.json file. You'll want to access this data using a json server. In order to do this, run
* npm start

All the characters live in
http://localhost:3000/characters path
All the foods in
http://localhost:3000/foods path


## STEP 2: Render all the characters on the page

Character information should include name, image, appetite and status and foods eaten

## STEP 3: Feed the children

Somewhere on the page there should be a form which has 2 `<select />` elements: one for characters and one for foods.


On selecting a character and a food the food name and sustenance value should appear on the list of foods eaten for that character. Each food item should have a delete button to remove that food item from that characters list.


## STEP 4: Declare status

If the character doesn't have any foods in the list or the sustenance value of the foods is less than the characters appetite their status should be "I'm hungry", If the combined sustenance value for the foods eaten is greater than characters appetite, the status should say "I'm full"


## STEP 5: Add more food items

Create a form to add a food item to the database and render a that food in the dropdown list of foods

## STEP 6: Add appetite

Add a way to increase the appetite value for each child which should also make a patch request to the server and the new value should render on the page.
