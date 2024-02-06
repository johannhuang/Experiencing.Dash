# Trying.Dash

This is also a companion article about this project at https://johannhuang.com/articles/uuid/452ad080-021a-466b-bccc-5ccfdd4e987c [Using Python Dash to Develop Data Applications for the Web].


## Dash

What is Dash?

* A product made by Plotly to make using Plotly.js and Plotly.py easier for the web.
* An integrated solution for data visulization on the web
    * encompasses Flask (including Jinjia2 etc.), Plotly.py as well as Plotly.js 


## App Environment

```sh
python --version

pip install dash
# collected packages: dash-table, dash-html-components, dash-core-components, zipp, urllib3, typing-extensions, tenacity, six, setuptools, packaging, nest-asyncio, MarkupSafe, itsdangerous, idna, colorama, charset-normalizer, certifi, blinker, Werkzeug, retrying, requests, plotly, Jinja2, importlib-metadata, click, Flask, dash
pip install pandas
# collected packages: pytz, tzdata, python-dateutil, numpy, pandas
pip install dash-bootstrap-components
# collected packages: dash-bootstrap-components
```


## Running the App

```sh
python app.py
# Dash is running on http://127.0.0.1:8050/
```
