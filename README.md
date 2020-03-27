# keras_dl_restapi

## Install Redis

$ wget http://download.redis.io/redis-stable.tar.gz
$ tar xvzf redis-stable.tar.gz
$ cd redis-stable
$ make
$ sudo make install 

### To start redis server
$ redis-server

## Install all dependencies in a virtual environment for Python3
$ pip install -u requirements.txt

## USAGE
Start the server:
$ python run_keras_server.py

## Submit a request via cURL:
$ curl -X POST -F image=@jemma.png 'http://localhost:5000/predict'

## Submita a request via Python:
$ python simple_request.py 


Credits:
The code in this repository is based on Blog tutorial of Computer Vision GOD Adrian Rosebrok check it out https://www.pyimagesearch.com/2018/01/29/scalable-keras-deep-learning-rest-api/