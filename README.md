- flask --app flaskr --debug run 
  run the server

- flask --app flaskr init-db 
  initialize the database

- coverage run -m pytest
  measure the code coverage of your tests.

- coverage report
  view a simple coverage report in the terminal


- python setup.py bdist_wheel
  build server

- waitress-serve --call 'flaskr:create_app'
  run server as production mode