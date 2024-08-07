# My_Blog_django

![action status](https://github.com/Kolyanuss/My_Blog_django/actions/workflows/django.yml/badge.svg)

## Project Description
My_Blog_django is a project designed to help understand and practice the basics of Django, a high-level Python web framework. This project includes various labs and exercises to build and improve your Django skills.

## Prerequisites
- Python 3.11

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Kolyanuss/My_Blog_django.git
   cd My_Blog_django
   ```

2. Create a virtual environment:
   ```sh
   python -m venv myvenv
   ```

3. Activate the virtual environment:
   - **Windows**:
     ```sh
     myvenv\Scripts\activate
     ```
   - **macOS/Linux**:
     ```sh
     source myvenv/bin/activate
     ```

4. Install the required packages:
   ```sh
   pip install -r requirements.txt
   ```

5. Apply database migrations:
   ```sh
   python mysite\manage.py migrate
   ```

6. Collect static files:
   ```sh
   python mysite\manage.py collectstatic
   ```

## Running the Project

Run the Django development server:
   ```sh
   python mysite\manage.py runserver
   ```

## Deactivating the Virtual Environment

When you're done working on the project, you can deactivate the virtual environment by running:
```sh
deactivate
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
