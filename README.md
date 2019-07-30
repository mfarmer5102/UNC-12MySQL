# **UNC Assignment #10 - NodeJS and MySQL (Node)**
> Created by Matthew Farmer

## About
This application, titled 'Bamazon', is an application where a user can access an artificial shopping website as either a customer or a manager. As a customer, the user can make purchases and deplete the company's inventory. As a manager, the user can check low inventory, restock low inventory, or add new items.

## Features

### Customer View
`node bamazon.js`

![ customer](/demoMedia/bamazon.mov)

Run the above command to access Bamazon as a customer. Make purchases and deplete the company's inventory. Click the link above to access the download link for a demonstrative video.

### Manager View
`node bamazonManager.js`

![ manager](/demoMedia/bamazonManager.mov)

Run the above command to access Bamazon as a customer. Find items in the inventory with stock quantities less than five, add more inventory to existing items, and add new items to the company's available inventory. Click the link above to access the download link for a demonstrative video.

## Additional Information

### Technologies Used

This application is built on NodeJS and uses MySQL as its database. NPM packages that it uses are MySQL (for interacting with the SQL database through Node) and Inquirer (for gathering input from the user in the terminal).
