# Ticketing System Backend

This repository contains the backend for a ticketing system built using Django. 

## Installation

1. Clone the repository:

```bash
git clone https://github.com/ChetanSureka/ticket-system-backend.git
```

2. Navigate to the project directory:

```bash
cd ticket-system-backend
py -m venv venv
venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Perform database migrations:

```bash
python manage.py migrate
```

5. Create a superuser for accessing the admin interface:

```bash
python manage.py createsuperuser
```

6. Run the development server:

```bash
python manage.py runserver
```

The backend server should now be running locally at `http://localhost:8000`.