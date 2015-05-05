- update apt repo (apt-get update)
- sudo apt-get install libpq-dev postgresql-client-9.4 python-dev python-pip git nginx
- Create user
- Create /srv/DjangoCMSDemo owned by django
- chmod /srv/DjangoCMSDemo 0770
- Clone into /srv/DjangoCMSDemo
- git clone https://github.com/gumaerc/DjangoCMSDemo.git
- sudo pip install -r requirements.txt
- make /run/gunicorn and chown to django
- apt-get install nginx
- 


- apt-get install python-pip
- pip install -U pip

Use CFN to make sure the resources we need are available.
    Those dont get to escape from source control
    VPCs
    Subnets
    Security Groups
    RDS
    Key Pairs?


