# WebAppFlask
This is an example web application using a flask. I run this off my WSL.

## PreReqs
1. apt-get update
2. apt-get install -y python
3. apt install -y python3-pip
4. pip3 install flask

## To Run the app
1. Make a directory and file called my app 
  cat > myapp.py
2. Paste in the code from myapp.py
3. Run the following: FLASK_APP=myapp.py flask run --host=0.0.0.0
4. Open up a browser and browse to http://<127.0.0.1>:5000/ (or the rlevant IP)
