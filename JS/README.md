# NODEJS backend
### using express, cors and nthline
-----
runs on port **3000**
requires 'yarn install' for the dependencies to work properly
-----
handles 2 requests as requested!
1) sha256: a POST request that receives in json **a** and **b** (either number or string) and returns a+b in sha256 format in a json with key **c**
2) write: a GET request that receives the query param 'line' and returns the line's line from the file.txt in the main folder of the project in plain text

each request handles possible errors and returns appropriate error codes and messages.

other requests will face **404** error!
