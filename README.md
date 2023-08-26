
# Django Quiz App

Welcome to the Django Quiz App! This is a web application built using the Django framework that allows users to take quizzes on various programming languages. Users can select a category and submit their answers. The app provides immediate feedback on whether the selected answer is correct or not.

## Features

- Select a quiz category from a list of programming languages.
- Submit answers and receive instant feedback on correctness.
- User-friendly alert messages for correct and incorrect answers.
- AJAX-based interaction to provide a seamless experience.

## Installation


1.Clone the Repository:

  Open your terminal and navigate to the directory where you want to store your project. Then, clone the repository:

  git clone https://github.com/yourusername/django-quiz-app.git
  cd django-quiz-app


2.Create and Activate a Virtual Environment:

  Set up a virtual environment to isolate your project's dependencies:
 
  On macOS and Linux:
  python3 -m venv venv
  source venv/bin/activate
  
  On Windows (using Command Prompt):
  python -m venv venv
  venv\Scripts\activate

3.Install Dependencies:

  While your virtual environment is active, install the required packages listed in the requirements.txt file:

  pip install -r requirements.txt
  Run Migrations:

4.Apply the database migrations to set up the database schema:

  python manage.py migrate

5.Create a Superuser (Optional):

  If you want to access the Django admin interface to manage the app, create a superuser account:

  python manage.py createsuperuser
  Follow the prompts to set a username, email, and password.

6.Start the Development Server:

  Launch the Django development server:

  python manage.py runserver
  Your app should now be accessible at http://127.0.0.1:8000/.

7.Usage:

  Open your web browser and go to http://127.0.0.1:8000/ to access the app.
  Select a quiz category from the available options.
  Answer the quiz questions by selecting the correct option.
  After submitting an answer, an alert message will indicate whether the answer is correct or not.
  Contributing:

If you're interested in contributing to the project, feel free to follow the guidelines mentioned in the README.

Remember that this guide assumes you have Python and Git already installed on your system. If not, you'll need to install them first.

                                                       *Thank You*
