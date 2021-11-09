# Assignment4-group-project
Web-server with parser and with connection to DBMS  
Team: Aisha Bazylzhanova(SE-2004), Arysbay Dastan(SE-2004) 

## Installation 

To install, you need to download webServer.py, database.py and templates from the repository and save them in the same folder. 

## Usage 

In database.py file you need to provide your data
   ```python
   app.config['SQLALCHEMY_DATABASE_URI'] = 'postgresql://YourUsername:YourPassword@localhost/NameOfYourDatabase'
   ```

When you can run webServer.py
   ```python
   C:\<your>\<path>\<to>\<the>\<folder>\webServer.py
   ```
   
In /webpage route you provide name of needed coin. When you enter the name of the coin and click the button, you will be automatically redirected to /coin route.
Parser will find news about entered coin and store them in database. After that you will see all recorded news about entered coin. 
  
   
## Examples 

```python
C:\Users\abazy>C:\Users\abazy\source\repos\ProjectsPython\project4\project\webServer.py
 * Serving Flask app 'database' (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: on
 * Restarting with stat
 * Debugger is active!
 * Debugger PIN: 190-195-588
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```
   
```python
http://127.0.0.1:5000/webpage
#Name:
#Sumbit
```
   
```python
http://127.0.0.1:5000/coin
#<All needed news>
```
LICENSE ✔

requirements.txt ✔

src/ ✔

test/ ✔
