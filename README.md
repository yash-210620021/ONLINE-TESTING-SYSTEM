# Online Testing System

## Overview
The Online Testing System is a web-based platform built using Django that allows users to create and participate in online tests. The system provides features for administrators to manage tests and users, as well as for participants to attempt tests and view their results.

---

## Features
- **User Management**:
  - Admins can add, edit, and remove users.
  - Secure user authentication with login and logout functionality.

- **Test Management**:
  - Create, update, and delete tests and questions.
  - Define time limits for tests.

- **Test Participation**:
  - Users can take assigned tests.
  - Auto-submission upon timeout.

- **Result Analysis**:
  - View scores and detailed performance reports.

---

## Technologies Used
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (default, configurable to other databases like MySQL or PostgreSQL)
- **Others**: Bootstrap (for styling), Django Rest Framework (optional for API support)

---

## Installation

### Prerequisites
- Python (>= 3.8)
- pip (Python package installer)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/online-testing-system.git
   cd online-testing-system
   ```

2. Create a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate   # On Windows: env\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply migrations:
   ```bash
   python manage.py migrate
   ```

5. Create a superuser (for admin access):
   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server:
   ```bash
   python manage.py runserver
   ```

7. Open the application in your browser:
   ```
   http://127.0.0.1:8000/
   ```

---

## Usage

### For Admins
1. Log in to the admin panel at `http://127.0.0.1:8000/admin/`.
2. Manage users, tests, and questions.
3. Assign tests to users.

### For Users
1. Log in using your credentials.
2. View assigned tests and start the test.
3. Submit answers and review results.

---

## Folder Structure
```
.
├── online_testing_system/   # Main Django app
├── templates/              # HTML templates
├── static/                 # Static files (CSS, JS, images)
├── db.sqlite3              # Default SQLite database
├── manage.py               # Django management script
├── requirements.txt        # Python dependencies
```

---

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact
For any questions or feedback, feel free to reach out at yashraj21patna@gmail.com.
