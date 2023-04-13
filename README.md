# What is this project?
It's a Single Page Application (SPA) for getting pieces of information on the https://swapi.dev/ website.

On the SWAPI we can find all information about the Star Wars incredible series.

I developed this project to test my technical skills during a job application.

**Usage** guide can be found down below, keep reading! 🙂 

## Menus:
- People (List of People)
- StarShips (List of StarShips)
- Planets (List of Planets)

### 🔎 Search filters:
name: The name of the Person

## BackEnd API with PHP
- /person/{search} => Return a list of people with {search} on name.
- /people/{page} => Return a list of 10 people. {page} default = 1
- /planets/{page} => Return a list of 10 planets. {page} default = 1
- /starships/{page} => Return a list of 10 starships. {page} default = 1

## 🆗 watch Next Steps
In this simple project, there are some improves that I will do affter:

- "films": "https://swapi.dev/api/films/",
- "species": "https://swapi.dev/api/species/",
- "vehicles": "https://swapi.dev/api/vehicles/"

## 🚀 Stack
- React
- PHP 8.1
- Bootstrap 5

## 🧑‍💻 Running the App
Simply run the command below, and it should be available at http://localhost:[PORT], ready for you to make requests.
```
git clone https://github.com/ed2ti/flighthub-swapi-react-php
npm install or yarn install

1) PHP
Go to src/backend and run php -S localho:8080

2) REACT
Go to src and run yarn start
