# To-Do List
A simple To-Do list web application built with Django. This application allows users to view and add tasks to their personal to-do list.

## Requirements
- Python 3.12.4 or higher
- Django 5.1.4 or higher

## Setup Instructions
Follow these steps to get the project running locally.

### 1. Clone the Repository
Clone the repository to your local machine:

```
git clone https://github.com/Aanushka001/To-do-List
cd todo_list
```

### 2. Install Dependencies
Install the required Python packages using pip:

```
pip install django
```

### 3. Run Migrations
Once dependencies are installed, run Django migrations to set up the database:
```
python manage.py migrate
```

### 4. Run the Development Server
Start the Django development server:
```
python manage.py runserver
```
The application should now be accessible at [http://127.0.0.1:8000/](http://127.0.0.1:8000/).

### 5. Access the Application
Open your browser and navigate to [http://127.0.0.1:8000/](http://127.0.0.1:8000/). You can now:
- View the list of tasks.
- Add new tasks by clicking the "Add New Task" button.

## Usage
- **Add New Task**: Click the "Add New Task" button to open a form where you can add a new task.
- **Task List**: Tasks are displayed in a list format, and you can interact with them.

## Development
To contribute to the project, follow these steps:
- Fork the repository.
- Create a new branch.
- Make your changes and submit a pull request.

## Running Tests
If you have tests configured, run them with the following command:
```
python manage.py test
```

## URL
Once the server is running, the application will be available at:  
[http://127.0.0.1:8000/](http://127.0.0.1:8000/)
