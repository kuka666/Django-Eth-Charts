# Authentication-flask-psql
Blockchain analytics tool using Django![image](https://user-images.githubusercontent.com/80199144/152834294-4a743b07-213d-4157-bb57-f0cfed651102.png)


### Instalation
Install our repoisitory 
```bash
https://github.com/kuka666/Django-Eth-Charts.git
pip install -r requirements.txt

Also create table in postgresql:

Create the database with name eth
python manage.py makemigrations python manage.py migrate python manage.py runserver
```

```bash
#change your setting
DATABASES = { 'default': { 'ENGINE': 'django.db.backends.postgresql', 'NAME': 'database name', #YOUR DATABASE NAME 'USER': 'postgres', #USER NAME 'PASSWORD': 'postgresql password', #YOUR PASSWORD 'HOST': 'localhost', } } 

```
### Usage
```bash
python manage.py runserver
```

### in the 19 and 20 rows write the usernmae and password
```bash
run the server in compilator 
http://127.0.0.1:8000/       for bar chart
http://127.0.0.1:8000/pie/   for pie chart
http://127.0.0.1:8000/line/  for line chart
```



### Examples

Usage examples:
```python
# get the bar chart
http://127.0.0.1:8000/ 
```
![1](https://user-images.githubusercontent.com/80199144/152835054-e8bd79c4-bb70-4313-91a1-0f2428284d25.jpg)
```python
# get rhe pie chart
http://127.0.0.1:8000/pie/
```
![2](https://user-images.githubusercontent.com/80199144/152835118-568cd1c0-81be-427c-806e-2ee4183cef71.jpg)


```python
# get the line chart
http://127.0.0.1:8000/line/ 
```
![3](https://user-images.githubusercontent.com/80199144/152835154-1650e2b3-964f-4f81-8cea-b87eff05df74.jpg)





## License
[MIT](https://choosealicense.com/licenses/mit/)
