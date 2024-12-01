# Student Management System
A simple and efficient Student Management System developed to manage student records, course enrollment, and results. This system provides functionalities to add, update, and manage student information, making it easier for administrators and educators to handle student data.

## Features

- **Student Information**: Add, edit, and manage student details.
- **Course Enrollment**: Enroll students in courses and manage course registrations.
- **Result Management**: Record and manage student results.
- **User Authentication**: Secure login system for administrators and users.
- **Database Integration**: Store and retrieve data from a database.

## Technologies Used

- **Backend**: Django
- **Frontend**: HTML, CSS, JavaScript
- **Database**: SQLite (can be configured to other databases)
- **Version Control**: Git, GitHub

## Installation

### Clone the repository:

```bash
git clone https://github.com/S-i-m-a/Student-Management-System.git
```

### Navigate to the project directory:

```bash
cd Student-Management-System
```

### Install required dependencies:

Make sure you have Python 3 and pip installed. Then, install the required dependencies by running:

```bash
pip install -r requirements.txt
```

### Database Setup:

Run the following commands to set up the database:

```bash
python manage.py makemigrations
python manage.py migrate
```

### Running the Development Server:

Start the development server:

```bash
python manage.py runserver
```

You can now access the application at `http://127.0.0.1:8000/` in your browser.

## Usage

1. **Sign Up/Login**: Create an account or log in as an administrator to manage the system.
2. **Add Students**: Use the admin panel to add, edit, or remove student records.
3. **Enroll Students**: Assign students to courses through the admin interface.
4. **Manage Results**: Record and view student results.
