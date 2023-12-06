# Student record managenment system

### I would like to extend my sincere thanks to Adil Mohak for providing the code on Github.It has greatly benefited our project.
### We made modifications to the source code provided by Adil Mohak. Firstly, we implemented the code on the PyCharm platform instead of Visual Studio Code, as used by Adil Mohak. Additionally, our database has some slight differences.
### Furthermore, we have conducted testing on the website, and we have already provided the testing plan and testing report.

### Demo video: https://youtu.be/KKIeRXwZ-Sw
### Setup video: https://youtu.be/gMJfENDEyUs
### Please subscribe his Youtube channel.He is a very nice guy: https://www.youtube.com/@adilmohak/videos


![dj-lms-dashboard](https://user-images.githubusercontent.com/60693922/212262964-5b5f2cb9-59b6-4be8-bf29-63a5265a7a9e.png)

Current features
(!=important)
----------------
* News And Events
* The admin can Add Students(!)
* The admin can Add Lecturers(!)
* Students can Add and Drop courses
* All user can update and view their profile.(!)
* Lecturers submit students score (Attendance, Mid exam, Final exam, assignment)(!)
* The system calculat students Total, Avarage, point, and grade automaticaly
* Also, the system tells the student whether he/she pass, fail or pass with a warning
* Assessment result
* Grade result(!)
* Upload video and documentations for each course
* PDF generator for students registration slip and grade result
* Storing of quiz results under each user
* Question order randomisation
* Previous quiz scores can be viewed on category page
* Correct answers can be shown after each question or all at once at the end
* Logged in users can return to an incomplete quiz to finish it and non-logged in users can complete a quiz if their session persists
* The quiz can be limited to one attempt per user
* Questions can be given a category
* Success rate for each category can be monitored on a progress page
* Explanation for each question result can be given
* Pass marks can be set
* Multiple choice question type
* True/False question type
* Essay question type
* Custom message displayed for those that pass or fail a quiz
* Custom permission (view_sittings) added, allowing users with that permission to view quiz results from users
* A marking page which lists completed quizzes, can be filtered by quiz or user, and is used to mark essay questions


# Pre-requisites:

> The os system is Windows 10.
> As mentioned in the original work, the project requires the installation of Python 3 and PostgreSQL database. We have installed the Python 3.11 and PostgreSQL 16.1 with Stack Builder.
> For further website development,we use PyCharm Community Edition.

- [Visual Studio Code any version u like](https://code.visualstudio.com/download)(This is what original creator using)
- [Pycharm newest version](https://www.jetbrains.com/pycharm/download/other.html)
- [Any Python-3 version](https://www.python.org/downloads/)
- [PostgreSQL database](https://www.postgresql.org/download/)

# Installation option 1 (provided by original owner)

- Clone the repo with `git clone https://github.com/adilmohak/django-lms.git`

- Create and activate a python virtual environment

- `pip install -r requirements.txt`

- Create `.env` file inside the root directory and include the following variables
```config
DB_NAME=[YOUR_DB_NAME]
DB_USER=[DB_ADMIN_NAME]
DB_PASSWORD=[DB_PASSWORD]
DB_HOST=localhost
DB_PORT=
USER_EMAIL=[YOUR_EMAIL]
USER_PASSWORD=[EMAIL_PASSWORD]
STRIPE_SECRET_KEY=LEAVE_THIS_BLANK_FOR_NOW
STRIPE_PUBLISHABLE_KEY=LEAVE_THIS_BLANK_FOR_NOW
```

- `python manage.py makemigrations`

- `python manage.py migrate`

- `python manage.py runserver`

Last but not least, go to this address http://127.0.0.1:8000

# Installation option 2 by our team

- download the source from `https://github.com/adilmohak/django-lms`

- Open the file with PyCharm Community Edition 2023.1

- Create `.env` file inside the root directory and include the following variables
```config
DB_NAME=django_sms_data
DB_USER=postgres
DB_PASSWORD=1
DB_HOST=localhost
DB_PORT=5433
USER_EMAIL=smtp.gmail.com
USER_PASSWORD=123456
STRIPE_SECRET_KEY=LEAVE_THIS_BLANK_FOR_NOW
STRIPE_PUBLISHABLE_KEY=LEAVE_THIS_BLANK_FOR_NOW
```

- `python manage.py makemigrations`

- `python manage.py migrate`

### Create admin account 
- `python manage.py createsuperuser`

- `python manage.py runserver`

Finally, you will get this address http://127.0.0.1

# References
- Mohak, A. (2023). Learning management system using django web framework. [online] GitHub. Available at: https://github.com/adilmohak/django-lms

# Contributing
Contributions are welcome. For major changes, please open an issue first
or submit a pull request to discuss what you would like to change.

# License
This project is licensed under the terms of MIT license. 

