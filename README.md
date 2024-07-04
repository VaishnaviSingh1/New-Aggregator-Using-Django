New Aggregator Using Django
----
This project is a news aggregator developed using Django, which scrapes news headlines from a specified source and displays them on a web page.

**Home Page**
![newAggregator1](https://github.com/VaishnaviSingh1/New-Aggregator-Using-Django/assets/98222001/705758e3-1856-4dcb-a005-266acb645c1f)

**News**




Installation
----
1. Clone the repository and navigate into the project directory:
```

git clone https://github.com/VaishnaviSingh1/New-Aggregator-Using-Django.git
cd New-Aggregator-Using-Django
```

2. Create a virtual environment and activate it:
```

python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```

3. Install dependencies using pip:
```

pip install -r requirements.txt
```


Running the Application
------

1. Make migrations and migrate to set up the database:

```
python manage.py makemigrations
python manage.py migrate
```
2. Start the development server:

````
python manage.py runserver
Visit http://localhost:8000/ in your web browser to view the application.
````

Usage
-------

1. Scraping News

To scrape news headlines, use the /scrape/<source-name> endpoint, where <source-name> is the name of the source to scrape from.

2. Viewing News
   
Navigate to /news/ to view the scraped news headlines.

Technologies Used
---------
1. Python
 
2. Django
   
3. BeautifulSoup (for web scraping)
 
4. Requests (for making HTTP requests)
