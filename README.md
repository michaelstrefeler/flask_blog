# flask_blog

A blog site made with Flask 1.0.2

I made this site by following [Corey Schafer's flask series](https://www.youtube.com/watch?v=MwZwr5Tvyxo&list=PL-osiE80TeTs4UjLw5MM6OjgkjFeUxCYH)

## Getting started

```bash
git clone https://github.com/michaelstrefeler/flask_blog.git
cd flask_blog

# Install required libraries
python -m pip install -r requirements.txt

# Open python REPL and create database
python
>>> from flaskblog import db
>>> db.create_all()
>>> exit()

# Run web server
python run.py
```