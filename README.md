
Implementation of real-world application: https://github.com/gothinkster/realworld/ using Django and HTMX.

An in-depth discussion of this implementation can be found [here](https://danjacob.net/posts/anatomyofdjangohtmxproject/).

Tech Stack:

* [Django](https://djangoproject.com)
* [HTMX](https://htmx.org)
* [Alpine](https://alpinejs.dev)

To install and run locally:

```bash
# Create the python virtualenv
python -m venv venv

# Activate the virtualenv for the current shell
. venv/bin/activate

# Install the required python packages with pip
pip install -r requirements.txt

# Run the DB migrations
./manage.py migrate

# Start the application
./manage.py runserver
```


**Note: this is just a reference implementation and is not intended for production use.**
