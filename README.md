# elarning platform

Next, set up a virtual environment and activate it:

`python3 -m venv env && source env/bin/activate`

Install required packages:

`pip3 install -r requirements.txt`

Next, perform migration:

`python3 manage.py migrate --settings=website.settings.local`

The setup is complete. Run a local server with

`python3 manage.py runserver --settings=website.settings.local`

the platform be available at `localhost:8000`.

