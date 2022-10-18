### What Is REStFUL API?
- A REST API (also known as RESTful API) is an application programming interface that conforms to the constraints of REST architecture

### Why use rest API?
- One of the key advantages of REST APIs is that they provide a great deal of flexibility. Data is not tied to resources or methods, so REST can handle multiple types of calls, return different data formats and even change structurally with the correct implementation of hypermedia.

### Why Learn Rest API with Python?
- By using Python and REST APIs, you can retrieve, parse, update, and manipulate the data provided by any web service you're interested in.

### Why Python Is a Good Language for Developing Rest API?
- Python as a scripting language is fast and productive. You can create web-based applications quickly and the code is highly readable as the fundamental idea behind Python is to incorporate an easily readable code.

### Benefits of Using Rest APIs
- Lightweight. 
- One of the main benefits of REST APIs is that they rely on the HTTP standard, which means it's format-agonistic and you can use XML, JSON, HTML, etc. ...
Independent. 
- Another benefit of REST APIs is the fact that the client and server are independent. ...
Scalable and flexible

### What Is a Rest API Call?
- A RESTful API is an architectural style for an application program interface (API) that uses HTTP requests to access and use data. That data can be used to GET, PUT, POST and DELETE data types, which refers to the reading, updating, creating and deleting of operations concerning resources.

### What are API - Get, PuT, Post & Delete calls?
- GET, POST, PUT, PATCH, and DELETE are the five most common HTTP methods for retrieving from and sending data to a server. 

```python
# APIs with pyhton
# install requests
# pip install requests

import requests
# Get
requests_bbc_status_code = requests.get("https://www.bbc.co.uk/iplayer/live/bbcnews")

# check the outcome of our API call
print(requests_bbc_status_code.status_code)
```
### Task
```python
import requests

class Api:

    def __init__(self, postcode):
        self.url = "http://api.postcodes.io/postcodes/"
        self.postcode = postcode

- Not completed yet / complete tomorrow
```
