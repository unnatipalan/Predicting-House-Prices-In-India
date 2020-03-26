# Predicting-House-Prices-In-India
A project to predict house prices in lakhs (INR). The linear regression model is trained using data from house characteristics in Bangalore, India from kaggle.com. I have used a python flask server that uses the saved model to serve http requests. The website, built in html, css and javascript, allows user to enter home square ft area, bedrooms etc and it will call python flask server to retrieve the predicted price on an interactive web page. Inspired from youtube.com/codebasics and their tutorials.


# Installation
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install requirements.

```bash
pip install -r requirements.txt
```

# Usage

```bash
python server.py
```

# Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

# License
[MIT](https://choosealicense.com/licenses/mit/)
