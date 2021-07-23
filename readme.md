## Create Virtual Env
    $ python3 -m venv env    //m = module

## Activate Env
    $ source env/bin/activate 

## requirements.txt file
    $ touch requirements.txt
All the dependencies will go under requirements.txt file

## install dependencies
    $ pip install -r requirements.txt    //r = recursively


#### SQL DB

    $ python
    $ from app import db
    $ db.create_all()
    $ exit()

#### in (env)
    $ sqlite3 todo.db
    $ .tables
    $ .exit