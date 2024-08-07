# Background
## Overview
Django Rockstarter is a Python package designed to accelerate the setup of Django projects by automatically creating a robust, production-ready directory structure and essential configuration files. With built-in support for django-environ to manage environment variables securely and whitenoise to handle static files efficiently, Rockstarter ensures your Django projects are well-prepared for deployment.

## Key Features
- Production-Ready Structure: Automatically sets up a comprehensive directory structure tailored for Django projects, adhering to best practices.
- Secure Configuration: Integrates django-environ to simplify the management and encryption of environment variables.
- Static Files Handling: Utilizes whitenoise to serve static files directly from your application, enhancing performance and security.
- Time-Saving: Eliminates the repetitive task of manually setting up project directories and configuration, allowing you to focus on writing code.


# Setup

1. Install django rockstarter package

```
pip install git+https://github.com/aldyahsn/django-rockstarter.git
```

2. Init project
```
rockstarter run
```

3. Install dependencies
```
pip install -r requirements.txt
```

3. Move environ sample

```
mv .env.sample .env
```

4. Migrate
```
python manage.py migrate
```

5. Run project
```
python manage.py runserver
```
