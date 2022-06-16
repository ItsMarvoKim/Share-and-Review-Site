# Share and Review Site(SARS)

## Author

Marvin Kimathi

## Description

SARS is a web application that enables users to post/share websites and other web-based projects as well as review posted projects.

## User Story

* A user can view posted/shared projects and their details.  
* A user can post a project to be rated/reviewed.
* A user can rate/ review other users' projects.  
* Search for projects.  
* View projects overall score.
* A user can view their profile page  

### Cloning

* In your terminal:

          $. git clone https://github.com/ItsMarvoKim/Share-and-Review-Site

## Running the Application

* Install virtual environment using `$ python3 -m venv --without-pip virtual`

* Activate virtual environment using `$ source virtual/bin/activate`

* Download pip in our environment using `$ curl https://bootstrap.pypa.io/get-pip.py | python`

* Install all the dependencies from the requirements.txt file by running `python3 pip install -r requirements.txt`

* Create a database and edit the database configurations in `settings.py` to your own credentials.

* Make migrations

        $. python manage.py makemigrations 
        $. python3 manage.py migrate 

* To run the application, in your terminal:

        $. python3 manage.py runserver

## Testing the Application

* To run the tests :

        $. python3 manage.py test 

## Technology used

* Python3
* Django
* Heroku

## Known Bugs

* There is no known bugs but incase you find out please contact me at issmavokim@gmail.com

## Deployment

With all environment variables changed to suit your local copy of this repository, deploy the application to [Heroku] to see it live or simply run it locally
  (virtual) $ python3.8 manage.py runserver

## License

This project is licensed under the MIT License [LICENSE.md](LICENSE.md)
