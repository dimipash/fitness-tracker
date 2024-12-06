# Fitness Tracker

## Project Description
A comprehensive web-based fitness tracking application built with Django, allowing users to log and monitor their workout sessions, track exercises, and visualize fitness progress.

## Key Features
- User authentication and profile management
- Workout session tracking
- Exercise logging with detailed metrics
- Progress visualization through charts
- Performance tracking and goal setting

## Technical Stack
- Python 3.10+
- Django 4.2
- PostgreSQL
- Bootstrap 5
- Chart.js

## Installation

### Prerequisites
- Python 3.10+
- pip
- virtualenv

### Setup Steps
1. Clone the repository
```bash
git clone https://github.com/dimipash/fitness-tracker.git
cd fitness-tracker
```

2. Create virtual environment
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Database Setup
```bash
python manage.py migrate
python manage.py createsuperuser
```

5. Run Development Server
```bash
python manage.py runserver
```

## Contributing
1. Fork the repository
2. Create your feature branch
3. Commit changes
4. Push to the branch
5. Create a Pull Request

## License
MIT License

## Screenshots
[Future: Add application screenshots]