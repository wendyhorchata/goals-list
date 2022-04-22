 ## Goals List 
 My Project is a simple website that allows the user to write personal goals. They will be able to delete a goal once they reached it, update and edit a goal as well. 

## Routes
 Get “/goals” = > renders index view listing

Get “/goals/list/new” = > renders new view with type schema in a form

Delete “/goals/list/:id => find a product by ID and deletes from database

Put “/goals/list/:id => update a product ID

Post “goals/list” => add a product to the database

Get “/goals/list/:id/edit” => render edit view with type schema to edit  

Get “/goals/list” => render show view listing all types currently stored in database

 
## Model Schema

Const type = new schema  {(

name: { type: String, required: true, unique: true},
description: { type: String, required: true},
img: { type: String},
price: { type: number, required: true} ,
qty: { type: number, required: true} ,



## Schedule

Day 1: Get project approved and create a game plan on how to start writing my code
Day 2: Complete Crud App with MVP
Day 3: Touch base with Squad Leader with any help I might have / work on CSS
Day 4: Deploy App on Heroku

