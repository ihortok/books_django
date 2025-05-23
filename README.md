### Requirements

- Python 3.13.3
- pip

### Setup

#### Create and activate virtual environment

```bash
python -m venv venv
source venv/bin/activate
```

#### Install dependencies

```bash
pip install -r requirements.txt
```

#### Run migrations

```bash
python manage.py migrate
```

#### (Optional) Create a superuser for admin access

```bash
python manage.py createsuperuser
```

#### Start the server

```bash
python manage.py runserver
```
