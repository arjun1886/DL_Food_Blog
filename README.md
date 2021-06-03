# Deep Learning aided food blog

Food blog website using Vanilla Javascript, HTML, CSS front end and Flask-MongoDB Backend. Users can sign up to the website and upload posts of food which involves uploading photos, writing descriptions and captions. Users can be searched for and their posts and can be commented on. Using Resnet50 object detection the food can be recognized and their names returned with hashtags to provide some captioning automation.

1) Setup flask on your machine
2) Setup MongoDB and create the collections 
3) Run api.py, image.py, ml.py as 3 separate flask servers
4) The REST Apis are part of the api.py flask server.
5) The image.py server is used as the ML component(Food recognition) in the project.
