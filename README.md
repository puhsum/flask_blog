# Flask Blog

A simple blog application built with Flask.

## Features

- Create, read, update, and delete blog posts
- SQLite database for data storage
- Bootstrap for styling
- Responsive design

## Installation

1. Clone the repository:
```bash
git clone https://github.com/puhsum/flask_blog.git
cd flask_blog
```

2. Create a virtual environment and activate it:
```bash
python -m venv env
source env/bin/activate  # On Windows use: env\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Initialize the database:
```bash
python init_db.py
```

5. Run the application:
```bash
flask run
```

Visit `http://localhost:5000` in your browser to see the blog.