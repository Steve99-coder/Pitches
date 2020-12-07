# PITCHES

## Author
 Stephen Nderitu

 ## Description
This is an application that allows users to use that one minute wisely. The users will submit their one minute pitches and other users will vote on them and leave comments to give their feedback on them.




## Behaviour Driven Development
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Start the page | **After the page loads** | View the post categories, Sign Up for an account or login|
| Sign Up| **Email**,**Username**,**Password** | Redirects you to login|
|  Login | **Email** and **password** | Redirect to main page and choose the category you want|
| Comment | **Comment** | input your comment|
| Submit |  | Saves the comment|

## Development Installation

* Git clone the repo at
  ```bash
  https://github.com/steve99-coder/Pitch.git
  ```
* Use Visual Studio Code or Editor of your choice and install the requirements to run the applicaton
  ```bash
  cd one-minute-pitch
  pip install -r requirements.txt
  ```
* Export your configurations and replace the username and password with your database
  ```bash
  export SQLALCHEMY_DATABASE_URI=postgresql+psycopg2://{User Name}:{password}@localhost/{database name}
  ```
* Run the application with the command below
  ```bash
  python3.8 manage.py server
  ```
* Test the application
  ```bash
  python3.8 manage.py test
  ```
Open the application on your browser `127.0.0.1:5000`.

## Technologies Used
- Python3.8

- PIP

- Flask

- Heroku

## Contact Info
For any assistance or suggestions reach me on stevenderitu99@gmail.com

## License 
[MIT](https://github.com/Steve99-coder/Pitches/blob/master/LICENSE.md)

 © [Stephen Nderitu](https://github.com/steve99-coder)


