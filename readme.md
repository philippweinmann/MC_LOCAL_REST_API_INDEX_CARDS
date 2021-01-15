# What is this repo?

Used as a local backend (fake-rest-api) for a project in the course Mobile computing and Internet of things.

Creating a real backend would be better, but I do not have the infrastructure nor do I want to spend money to host our api so I decided for a local one.

# How to install and run:

for a longer explanation on how it works: https://www.youtube.com/watch?v=1zkgdLZEdwM

1. install node-js
2. install json server: `npm install -g json-server`
3. download this repo and run with: `npm run json:server:index_cards` to launch the index cards database

# How to use on the frontend:

Like you would use any rest API. The port (3000) may vary especially if a reactjs application is running locally as well.

GET ALL INDEX CARDS
http://localhost:3000/index_cards

GET SINGLE INDEX CARD
http://localhost:3000/index_cards/1

FILTER INDEX CARDS BY TITLE
http://localhost:3000/index_cards?title=John

SORTING
http://localhost:3000/index_cards?\_sort=title&\_order=desc
http://localhost:3000/index_cards?\_sort=title&\_order=asc

# How to modify the database structure

if you want to add or remove an entry or rename an entry directly change the json file: index_cards.json`
