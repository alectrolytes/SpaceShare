# [SpaceShare](spaceshare.me)

  ###Working [Builds](https://travis-ci.org/DavidAwad/SpaceShare)! 


### This is a File sharing platform  meant to simplify file sharing between groups of people. 
### You go to spaceshare.me, upload your file, give it a number. 
### Others go to spaceshare.me/upload/number and it will give you the file. 

####Built using Flask, using mongodb with gridFS to store uploaded files.

##Dependencies 

1. In your terminal, 
```bash
pip install -r requirements.txt
```

## Run the server

1. run the Flask Server
```
cd [REPO LOCATION]
python __init__.py
```
2. Run Mongod with something like `./mongod --config mongodb.config`

3. Access app from localhost:5000 (wherever your terminal says it is)


## Other Useful Flask Examples To Learn what's happening :
##[File Input in Flask](http://runnable.com/UiPcaBXaxGNYAAAL/how-to-upload-a-file-to-the-server-in-flask-for-python) by [Michael Molina](http://runnable.com/u/mmolina)
##[Simple Flask Guest Book](https://github.com/x/Simple-Flask-Guest-Book) by [Devin Peticolas](https://github.com/x)
##[Flask Talk f2014](https://github.com/usacs/flaskTalkF2014) by [Vaibhav Vverma](https://github.com/v)
##[Flask Database Talk](https://github.com/kaushal/databaseTalk2014) by [Kaushal Parikh]()

## Special Thanks
### StackOverflow, Joel Pena, Devon Peticolas, and Wisdom Omuya from MongoDB made this app Possible. Thank you sincerely.   
