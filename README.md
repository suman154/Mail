# CS50W Project 3 - Mail
# Clone the repository
```sh
git clone https://github.com/suman154/Mail.git
```

# Navigate into the project directory
```sh
cd mail
```

# Create a virtual environment (optional but recommended)
```sh
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```

# Install dependencies
```sh
pip install -r requirements.txt
```

# Apply database migrations
```sh
python manage.py migrate
```

# Create a superuser (if applicable)
```sh
python manage.py createsuperuser
```

# Start the development server
```sh
python manage.py runserver
```

