## Overview
[Trellow](https://trellow.onrender.com/) is a [Trello](https://trello.com/) clone, which allows users to create project boards to manage their progress and organize tasks.

## Technologies used
**Frontend**
- React
- Redux
- JavaScript
- HTML
- CSS

**Backend**
- Flask
- Python
- PostgreSQL
- SQLAlchemy

## Technical Implementation
While building Trellow, I wanted to ensure that users would easily understand how to navigate and use the website features. Using AJAX, DOM manipulation, and error handling users would be notified immediately what actions were required to use the feature.

<img src= https://i.imgur.com/WxM4qkV.png alt='Error Handling' width='654px' height='380px'/>

<img src= https://i.imgur.com/hVRjIOf.png alt='Error Handling' width='643px' height='376px'/>

## Trellow setup
1. Clone this repository (https://github.com/bandrewi/trellow-onrender)
2. Install dependencies - `pipenv install --dev -r dev-requirements.txt && pipenv install -r requirements.txt`
3. Create a `.env` file based on the **.env.example** with proper settings required for the development environment
4. Setup PostgreSQL user, password and database and to make sure it matches the **.env** file
5. Get into pipenv, migrate the database, seed the database, and run the flask app using the following commands:
   * `pipenv shell`
   * `flask db upgrade`
   * `flask seed all`
   * `flask run`
6. To run the React App in development, checkout the [README](./react-app/README.md) inside the `react-app` directory.

## Features
Logged in users can perform the following action:
* View/Create/Update/Delete Boards
* View/Create/Update/Delete Lists
* View/Create/Update/Delete Cards

## Link to Wiki docs
https://github.com/bandrewi/trellow-onrender/wiki
