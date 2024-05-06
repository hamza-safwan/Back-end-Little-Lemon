# DineWise
DineWise is a one stop application for food businesses on which I am working as my portfoio project right from scratch to understand the whole process of software development and gain hands-on experience. Initially basic functionalities have been implemented like various bookings menu offerings being offered by food businesses. I am working to engineer a full fledge large scale, enterprise system backed by AI/ML intelligence.

## Steps to run the app

### 1. Install `pipenv`

```bash
pip install pipenv
```

### 2. Create a `.env` file in the root folder

```bash
# .env
DATABASE = YOUR_MYSQL_DATABASE_NAME
USER     = YOUR_USERNAME             # default is root
PASSWORD = YOUR_MYSQL_PASSWORD
HOST     = localhost                 # or 127.0.0.1
PORT     = 3306
```

### 3. Install dependencies

```bash
pipenv install
```

### 4. Make migrations

```bash
py manage.py makemigrations
```

### 5. Migrate

```bash
py manage.py migrate
```

### 6. Run the app

```bash
py manage.py runserver
```

### To run tests

```bash
py manage.py test tests
```
