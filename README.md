# LinkTree


![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray)  ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)  ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)   ![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black)  ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)  ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)  ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)  ![Babel](https://img.shields.io/badge/Babel-F9DC3e?style=for-the-badge&logo=babel&logoColor=black)  ![Redux](https://img.shields.io/badge/redux-%23593d88.svg?style=for-the-badge&logo=redux&logoColor=white)


![Home](https://user-images.githubusercontent.com/66418035/142405149-4275254a-1581-427e-b37a-e81fe98b940a.PNG)
![Read the Docs](https://img.shields.io/readthedocs/pip?style=plastic)
![GitHub commit merge status](https://img.shields.io/github/commit-status/mushahidmehdi/Full-Stack-Web-Application/main/c49a9cf916c11d163b7b4d1256b89c211793d6ee)
[![Python 3.6](https://img.shields.io/badge/python-3.8.8-blue.svg)](https://www.python.org/downloads/release/python-360/)


![Conda](https://img.shields.io/conda/pn/conda-forge/python)



## Technologies  

### Django (4)
 
We will use `Django` because of Model View Template `(MVT)` architecture which allow us to have control over all the incoming requests in `view file`, meanwhile, Objects Relational Mapper `(ORM)` will write all `SQL queries` and performed all `CRUD oprations` in accordance to `model schemas` in `model file` based on authorization level while making `makemigration` requests right before `commit` & we will easly integrate any frontend libray into django template in order to render the HTML. 

### Django REST framework (python)
To access the database from multiple types of Frontend devices we will create an REST API built in Django REST Framework where in `api file` we will write all CRUD oprations and gain completed control on all the incoming requests and how much authorization we have assigned to each request for instance from Superuser to a guest from Djano admin.


### ReactJS
ReactJS will be used to create UIs because the component base architecture in (MVC) with Single Page application promises high speed UI rendering by comparing against the `ReactJS virtual DOM` and only necessary changes will be fired into the `actual DOM` after any events triggered or state/props changes, also react follows both `DRY & KISS programing `principles better than any other frontend library.


### ReduxJS
Redux will be used to create `single source of truth` for all JavaScript objects which allow us to keep track of all the properties & states under single tree Store, this makes debugging very handy also prevent us to pass props across all the unneccessary components aka prop drilling.

### Webpack/Babelrc

Webpack will bundle all the js components into single bundle & Babelrc will be used to transpile `JSX` into Browsers compatible JavaScript especially before ES6 compatible browsers.



## How to use:
Follow each step below one after the another in Terminal.

#### Clone the Repo:
-  ```git clone https://github.com/mushahidmehdi/LinkTree.git```
-  ```cd LinkTree```


#### Create a virtuel env for Python 3.8 with pipenv:
-  ``` pip install pipenv ```

This will create a virEnv name after the folder e.g.Online-Auction-Website and also activate it.
-  ``` pipenv shell ```

#### Create a virtuel env for Python 3.9 with pipenv:
-  ``` pip install pipenv ```

To Create Virtual Envroment:
-  ``` pipenv --python 3.10 install  ```

To activate this Virtual Envroment:
-  ``` pipenv shell ```

#### Install Dependencies 
-  ``` npm install  ```
-  ``` pipenv install -r requirements.txt ```

#### Run the Server
-  ``` cd config ```
-  ``` python manage.py runserver ```



