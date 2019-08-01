# twitter

RESTful API endpoint to provide data from Twitter by scraping in real-time. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

github link for get clone or download repository (public repository)

```
github link: https://github.com/jimy1824/twitter.git

```

### Installing

1. Install python, project require python 3.6/3.7 install python
2. Create virtual environment
    1. Install pip first
        ```
        sudo apt-get install python3-pip
        ```
    2. Then install virtualenv using pip3
        ```
       sudo pip3 install virtualenv
        ```
    3. create a virtual environment
        ```
         virtualenv venv
        ```
        for specific Python interpreter  choice
        ```
          virtualenv -p /usr/bin/python3.6 venv
        ```
    4. Activate virtual environment
        ``` 
        source venv/bin/activate
        ```
3. Install requirements
```
command pip install -r requirements.txt
```

## Run Server
Run the server
```
python manage.py runserver
```

## Running the tests

Run test cases 
```
python manage.py test
```

## Built With

* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - For Scraping
* [Selenium](https://www.seleniumhq.org/) - Web Automation
* [REST](https://www.django-rest-framework.org/) - Used to generate RESTFul APIs



## Authors

* **Billie Thompson** - *Initial work* - [jimy1824](https://github.com/jimy1824)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.