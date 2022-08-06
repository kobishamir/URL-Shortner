# URL-Shortner
## URL Shortner based on python and Flask
### By Kobi Shamir

*That project still not finished and I still have some work to do*

**Please follow the next steps to make the URL-Shortner work:**


1. Clone project
2. In Terminal/CMD go to the directory where the project was downloaded
3. Install Flask: ```pip install flask hashids```
4. Run file **"init_db.py"** first - to build the DB with the table in the project directory
5. Run the file **"app.py"**
6. run the commands:
```    
       export FLASK_APP=app
       export FLASK_ENV=development
       flask run
```
(if working in windows CMD replace export with SET)

6. go to ```http://127.0.0.1:5000/```


*Since it is still not finished, some problems may occur, for now, the only solution I can offer is to stop the process
(ctrl + C) and repeat steps 2-5*
