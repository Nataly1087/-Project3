# Project3

## Online store with PostgreSQL on Django

## Django is the server-side component of an online store, responsible for the site's logic: managing product data, users, and orders, as well as processing user requests.
- Receives requests from the user (e.g., site navigation, adding an item to the cart) and sends an appropriate response.
- Interacts with the database to store and retrieve information about products (name, description, price), users (registration, authentication) and orders.
- The received data is passed to templates (views), which are responsible for generating the appearance of the pages that the user sees.

## Key Code Elements

## Models: Define the structure of data in the database.

## Views: Process user requests, retrieve data from models, and pass it to templates.

## Templates: Responsible for displaying data to the user. They contain HTML code with dynamic elements that are populated with data from views.

## Requirements:
- Django
- Docker
- Docker Compose 
- PostgreSQL

## Launch:
To launch the system, you need to:
- Install Django: poetry add django
- Install Docker and Docker Compose.
