# Polls web app using Django

## This app was made following the [Django tutorial](https://docs.djangoproject.com/en/2.1/intro/tutorial01/)

Users can vote on questions and see the results displayed. Administrators have access to a user-friendly admin interface that allows them to add and delete questions and choices.

### Steps to run:
1.Change directory to mysite/ and execute `python3 manage.py runserver` which starts the server on your local IP address `127.0.0.1` (or `localhost`) on port `8000`. The domain is accessible by 
going to `http://localhost:8000/`

2.To access the admin interface go to `http://localhost:8000/admin/` with username = `admin` and password = `admin`

3.To see the latest 5 questions go to `http://localhost:8000/polls/` and click on any one to vote. After voting you can see the results on the next page.
