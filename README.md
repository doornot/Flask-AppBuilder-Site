## The Site for flask-appbuilder

How to contribute:

```sh
# Create a virtual environment and activate it
python3 -m venv venv
source venv/bin/activate

# install requirements
pip install -r requirements.txt

# Create an admin user
flask fab create-admin

# flask env
export FLASK_APP=app
export FLASK_ENV=development

# Run dev server
flask run
```
