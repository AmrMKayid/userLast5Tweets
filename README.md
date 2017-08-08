# userLast5Tweets
Single web page application which retrieve the username’s latest 5 tweets

# How to install and run:
Using the terminal
```
pip3 install --user -r requirements.txt
```

then you need to export the API Key and API Secret
```
export API_KEY=Vra68cSg6DO81zaV0HCcjR6IQ
```
```
export API_SECRET=S3W2Ny2Jm7hqKU20jUrxziy62HqNEmdVR3dmztPootvDnurXEO
```

after that we need to set the flask_app
```
export FLASK_APP=application.py
```

Now we can run our program 
```
python3 -m flask run
```

You can now open the webpage on your local host http://127.0.0.1:5000/ 

Enter the @username and you will get the tweets


