# DJANGO TASK FORCE PROJECT (DTF)

## DTF Project Group Assignment for Bootcamp-13
In this project, we shall be demonstrating to students how to go about Django Installations, Use of some modules in Django eg PostgreSQL, RESTAPi, etc to the class.

# Pre-Installations
1. Create a folder for your project
2. git clone repo
3. Install dependencies;
    - Install _psycopg2_ using __pip install psycopg2__
4. Server configuration
    - configure server _setting_ to your own DB settings.
5. Make _python migrations_ for the DB
6. Install REST framework module using __pip install djangorestframework__

## Using the REST API
1. This API has two models, course and student
2. Configured locally to run at _http://127.0.0.1:8000_
    - Creating a Course (_http://127.0.0.1:8000/new_course/_)
        - use format __{"courseName":"Python"}__ and POST
    - Adding New Student (_http://127.0.0.1:8000/new_student/_)
    - List of all students (_http://127.0.0.1:8000/all_students/_)
    - Update Student (_http://127.0.0.1:8000/update_student/id_)
    - Delete Student (_http://127.0.0.1:8000/delete_student/id_)

## Screen-shots of API
1. All Students Display
 ![all student](https://github.com/Kitemaggwa-Shafic/django_task_force/assets/54108967/e33c0631-a1d0-4af4-9934-d50023f26264)

2. New Student
![New student](https://github.com/Kitemaggwa-Shafic/django_task_force/assets/54108967/33a5488c-1422-40c8-bce6-632d1ecb3374)


## Group Team Members:
1. Oliver Balyama
2. Kitemaggwa Shafic
3. Kamugisha Bruce
4. Dennis Emmanual Ssendagire
5. Kwizera Richard
