# airflow
1. Please activate the venv by `source venv/bin/activate`.
2. To indicate the airflow home directory by `export AIRFLOW_HOME=.`.
3. Initialise the database with command `airflow db init`. Only do this step if you haven't initialise the database
4. Once we have the db initialize, we need to create the users by `airflow users create --username admin --firstname firstname --lastname lastname --role Admin --email admin@example.org` then input the password.
5. If we want to run the scheduler then just open the new terminal and do the step 1-2 again after that just type `airflow scheduler`.
6. Next we can go to the airflow webserver with `airflow webserver -p 8080` and after that just need to input the username and password.
7. To shutdown the airflow webserver just type `Ctrl + C`.