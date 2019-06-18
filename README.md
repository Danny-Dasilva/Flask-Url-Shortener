# Flask-Url-Shortener

commands to remake the database

### Step 1 
change the database uri 
*in settings.py*
`SQLALCHEMY_DATABASE_URI =  'sqlite:///db.sqlite3' `

### Step 2
type ` python`
then
`from url_shortener import create_app
from url_shortener.extensions import db
from url_shortener.models import Link
db.create_all(app=create_app())`
