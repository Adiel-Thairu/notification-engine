# notification-engine
notification engine in python

step one: cd djangopush

step two: activate your virtual environment in the root folder
my_new\Scripts\activate.bat 

step three: create secure tunnel to your application in a second command-line window
ngrok http your_server_ip:8000

step four: run your server in the first command-line window
python manage.py runserver

step five:
use the address in the second command-line following the https:ngrok_secure_url -> your_server_ip to access your engine
