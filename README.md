# AITuring-Test


### Requirements

- Python 3.8.10
- React

--- 

## Back-end

### Installation steps

1. Ensure you have python3 installed
2. Clone the repository
2. Install docker and docker-compose
    [docker](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04)
    [docker-compose](https://docs.docker.com/compose/install/)
3. Install python3 virtual env `apt install python3.8-venv`
3. Install python3 pip `sudo apt install python3-pip`
3. create a virtual environment using `virtualenv env`
4. Activate the virtual environment by running `source env/bin/activate`
4. Upgrade setup tools to avoid errors `pip install --upgrade setuptools pip wheel`
4. Install Python3 and Mysql development header `sudo apt-get install python3-dev default-libmysqlclient-dev build-essential`
5. Install the dependencies using `pip install -r requirements.txt`
6. Run docker to mysql db `docker-compose up`
* To stop use `docker-compose stop`
7. Go to folder `AITuring-Test/backend`
8. Migrate existing db tables by running `python manage.py migrate`
9. Run the django collectstatic `python manage.py collectstatic`
10. Run the django development server using `python manage.py runserver`

### Access to admin

1. Go to folder `AITuring-Test/backend`
2. Create super user `python manage.py createsuperuser`
3. Follow instructions
- e.g.

    | user | password | Description |
    | ----- | ----- | ------ |
    | AITuring | AITuring | Admin |

### Results backend

- Swagger: [127.0.0.1:8000](127.0.0.1:8000)
- Admin django: [127.0.1:8000/admin](127.0.1:8000/admin)

--- 

## Front-end

### Setup local

- sudo apt install nodejs
- sudo apt install npm

### Installation steps
- npm install
- npm start

### Results frontend
- [127.0.0.1:3000](127.0.0.1:3000)

---

## Author 

[Jose David Caro](https://www.linkedin.com/in/josecarocantor/) |  [GitHub](https://github.com/josecaro02)
