# Drinks Info

Console based solution for drinks menu.
Developed using C# and MS SQL SERVER.
Used third-party vendor’s data is to make requests to their APIs

The API provider (https://www.thecocktaildb.com/api.php)

# Given Requirements:

- [x] drinks menu is provided by an external company. All the data about the drinks is in the companies database, accessible through an API
- [x] Should create a system that allows the restaurant employee to pull data from any drink in the database.
- [x] When the users open the application, they should be presented with the Drinks Category Menu and invited to choose a category. Then they'll have the chance to choose a drink and see information about it.
- [x] When the users visualise the drink detail, there shouldn't be any properties with empty values 


# Features

* API connection

	- Used seperate class DrinksService to handel API request and data serialization

* A console based UI 
  - ![Screenshot 2024-07-27 142027](https://github.com/user-attachments/assets/37d40b6f-802e-4b9f-ad9e-4242933d6ba9)

* According to category we list the drinks
  - ![Screenshot 2024-07-27 142056](https://github.com/user-attachments/assets/afbbd885-23bc-4fc6-ba98-799d959bddbe)
