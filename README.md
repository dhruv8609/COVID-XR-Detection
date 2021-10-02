# COVID-XR-Detection
Rest-API for detection of COVID-19 using chest radiography and CT_scans. Flask is used as a backend to support this project. Images are given
as input and prediction of each model is returned as output. 
[Flask](https://flask.palletsprojects.com/en/2.0.x/) 

## Requirements
- Flask
- Python 3.6
- Tensorflow 1.15

## Installation
After you cloned the repository, you want to create a virtual environment, so you have a clean python installation.
```
python -m venv env
```

After this, it is necessary to activate the virtual environment, you can get more information about this [here](https://docs.python.org/3/tutorial/venv.html)

You can install all the required dependencies by running
```
pip install -r requirements.txt
```

## More...
In a RESTful API, users access data from our application using the HTTP methods - GET, POST, PUT, DELETE.
Several endpoints are mentioned here:

Endpoint |HTTP Method| Result
-- | -- |--
`/` | GET | Getstarted
`/uploaded_xr` | POST | Returns results on Radiography images
`/uploaded_ct`| POST | Returns results on CT_scan images

### Work ahead ...
improving the model accuracies.
