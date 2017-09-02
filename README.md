# CS50-Finance
This is a modified version of my submission for the 7th Problem Set of Harvard University's Introduction to Computer Science course (CS50). The full details of the specifications may be viewed at [Problem Set 7 - C$50 Finance].

In this web application, the user may "buy" and "sell" stocks (essentially managing a portfolio of stocks) whose prices are based off of data from [Yahoo! Finance]. Since data is queried from Yahoo! Finance, checking of real stocks' actual prices at the moment of query is made possible.

My version of C$50 Finance used the following in its implementation:
- [Flask] (Python "microframework")
- [SQLite] (SQLAlchemy - for the database)
- [Yahoo! Finance] (for being main source of retrieval of stock quotes)
- [Flask-Heroku] (for setting configuration defaults for Heroku-esque environment variables)
- [Heroku] (for deployment)

The web application can be accessed at [ra-cs50-finance.herokuapp.com]. Feel free to explore its functionalities and send me an [email] if you find any bugs.

[ra-cs50-finance.herokuapp.com]: <ra-cs50-finance.herokuapp.com>
[Problem Set 7 - C$50 Finance]: <http://docs.cs50.net/problems/finance/finance.html>
[Yahoo! Finance]: <http://finance.yahoo.com/>
[Flask-Heroku]: <https://github.com/kennethreitz/flask-heroku/>
[Heroku]: <https://www.heroku.com/>
[SQLite]: <https://www.sqlite.org/>
[Flask]: <http://flask.pocoo.org/>
[email]: <mailto:reginaalyssa01809@gmail.com>