<h1>SQLAlchemy Practice</h1>

<h2>Objectives</h2>

<ol>
  <li>Integrate SQLAlchemy ORM into a Flask application</li>
  <li>Use SQLAlchemy to create appropriate tables and columns for your database</li>
  <li>Write SQLAlchemy queries and fetch records from a database</li>
  <li>Navigate relationships between tables</li>
</ol>

Basic setup: 
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt

DB setup:
$ dropdb cars
$ createdb cars
$ psql cars < database.sql
