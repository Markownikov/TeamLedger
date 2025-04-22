# Office Employee Management System

This is a Django-based web application for managing office employees. It allows users to perform the following operations:

- View all employees
- Add a new employee
- Remove an existing employee
- Filter employees based on specific criteria

## Features

1. **Employee Management**: Add, view, and remove employees.
2. **Filtering**: Filter employees by name, department, or role.
3. **Bootstrap Integration**: The application uses Bootstrap for responsive and user-friendly UI.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd ofc-emp-management-system-main/office_emp_proj
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations:
   ```bash
   python manage.py migrate
   ```

5. Run the development server:
   ```bash
   python manage.py runserver
   ```

6. Open your browser and navigate to `http://127.0.0.1:8000/`.

## Project Structure

- `emp_app/`: Contains the main application logic, including models, views, and templates.
- `office_emp_proj/`: Contains project-level settings and configurations.
- `db.sqlite3`: SQLite database file.
- `requirements.txt`: List of Python dependencies.

## Requirements

- Python 3.6+
- Django 3.2.11

## License

This project is licensed under the MIT License.