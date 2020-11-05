# pitch-world
## Author
[Washiko Kelvin](https://github.com/Washikokevv27)
# Description
This  is a flask application that allows users to post one minute pitches and also allows other users who have signed up and make a pitch. It also allows a person to signup to be able to access the functionalities of the application
## Live Link
[View Site](https://pitch-pop.herokuapp.com/)

## User Story

* Comment on the different pitches posted py other uses.
* See the pitches posted by other uses.
* Register to be allowed to log in to the application
* View pitches from the different categories.
* Submit a pitch to a specific category of their choice.
## BDD
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Load the page | **On page load** | Get all posts, Select between signup and login|
| Select SignUp| **Email**,**Username**,**Password** | Redirect to login|
| Select Login | **Username** and **password** | Redirect to page with app pitches based on categories and commenting section|
| Select comment button | **Comment** | Form that you input your comment|
| Click on submit |  | Redirect to all comments tamplate with your comment and other comments|
## Development Installation
To get the code..
1. Cloning the repository:
  ```bash
  https://github.com/Washikokevv27/pitch-world
  ```
2. Move to the folder and install requirements
  ```bash
  cd pitch-world
  pip install -r requirements.txt
  ```
3. Exporting Configurations
  ```bash
  export SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://{User Name}:{password}@localhost/{database name}
  ```
4. Running the application
  ```bash
  python3.8 manage.py runserver
  ```
5. Testing the application
  ```bash
  python3.8 manage.py test
  ```
Open the application on your browser `127.0.0.1:5000`.
## Technology used
* [Python3.8](https://www.python.org/)
* [Heroku](https://heroku.com)
## Known Bugs
* There are no known bugs currently but pull requests are allowed incase you spot a bug
## Contact Information 
If you have any question or contributions, please email me at [washikokevv27@gmail.com]
## License
* *MIT License:*
* Copyright (c) 2020 **KELVIN WASHIKO**