# Nearbyshops

The application can be used to search nearest shops.

## Download

To begin using this application use link below to get started.

[Download Nerbyshops](https://github.com/visse0001/Nearbyshops.git)

## Development setup

- create venv <br /> <br />
At the time of creating this app QGIS does not work with Python 3.7, so you will need a copy of Python 3.6.
- install Python 3.6
- install postgresql
after install posgresql we need to run command: <br />
sudo -u postgres psql <br />
CREATE USER user001 WITH PASSWORD ‘123456789’; <br />
ALTER ROLE user001 SUPERUSER; <br />
CREATE DATABASE gis; <br />
We have to check postgresql version: <br />
pg_config --version <br />
Please install postgis extensions using the below command: <br />
sudo apt-get install postgis postgresql-10-postgis-scripts <br />
Please use the postgis version same as your postgres db. <br />




## Usage


- python manage.py runserver

## Location

Location is hard-coded.

## Bugs and Issues

Have a bug or an issue with this application? Send an email to:
 
 san.kuczynska@gmail.com