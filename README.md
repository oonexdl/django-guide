### Web part

#### install pip

```shell
sudo apt-get install python-pip
```

#### install django

```shell
pip install Django
```

#### install mysql

```shell
sudo apt-get install mysql-server
```
#### install mysqlclient

```shell
sudo apt-get install python-dev libmysqlclient-dev
# if you are using python3 then you need to install python3-dev using the following command
# sudo apt-get install python3-dev
pip install mysqlclient
```

referrence:

- https://docs.djangoproject.com/en/1.11/intro/

### Web server part

#### install uwsgi

```shell
pip install uwsgi
```
#### install

```shell
sudo apt-get install nginx
```

referrence:

- http://uwsgi-docs.readthedocs.io/en/latest/tutorials/Django_and_nginx.html