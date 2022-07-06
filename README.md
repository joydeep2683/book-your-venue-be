# book-your-venue-be

### Project setup instructions are for Mac users only

#### Python virtual environment setup:

1. Download the exact python version - 3.10.0
2. Download pkg file install it and then you can check, binaries were installed in ```/usr/local/bin/```
3. You can go to ```/usr/local/bin/``` and check the pip versions and use the suitable versions for installation of the requirements.
4. Install virtualenv package - ```sudo pip3 install virtualenv``` (it should be installed in ```/usr/local/bin/```)
5. To Create an environment - go to the location where you want to create the environment. And run this command - ```virtualenv -p python3.10 venv-name```


#### Installing the dependencies:
1. ```pip3.10 install -r requirements.txt```


#### Setting up the database:
1. Download [postgres.app](https://postgresapp.com/) with postgresql 14
2. To access the database in the terminal open postgres app from the top ribbon and slect your database server from left panel
3. Double click on the *postgres* DB

#### Run the server:
1. ```python manage.py runserver```
