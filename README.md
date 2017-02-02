# Linux Server Configuration.
Description for project Linux Server Configuration

1. Server IP address 52.34.125.84 SSH port 2200
2. URL to project site [Item Catalog](http://ec2-52-34-125-84.us-west-2.compute.amazonaws.com/)
3. Bash history
    - grader's user bash history
    ```
    pwd
    ls -a
    mkdir .ssh
    ls -a
    touch .ssh/authorized_keys
    nano .ssh/authorized_keys
    chmod 700 .ssh
    chmod 644 .ssh/authorized_keys
    sudo apt-get update
    sudo apt-get upgrade
    sudo apt-get update
    sudo apt-get upgrade
    sudo /etc/ssh/sshd_config
    sudo nano /etc/ssh/sshd_config
    service sshd restart
    service ssh restart
    sudo service ssh restart
    ls
    ls -al
    sudo dpkg-reconfigure tzdata
    sudo ufw status
    sudo ufw default deny incoming
    sudo ufw default allow outgoing
    sudo ufw allow 2200/tcp
    sudo ufw allow www
    sudo ufw allow ntp
    sudo ufw enable
    sudo ufw status
    git
    sudo apt-get install git
    git
    sudo apt-get install apache2
    sudo apt-get install libapache2-mod-wsgi
    sudo apache2ctl restart
    sudo nano /etc/apache2/sites-enabled/000-default.conf
    sudo apache2ctl configtest
    sudo nano /etc/apache2/apache2.conf
    sudo apache2ctl restart
    sudo nano /etc/apache2/apache2.conf
    sudo apache2ctl restart
    python
    sudo apt-get install postgresql
    psql
    sudo psql
    sudo dpkg-reconfigure locales
    sudo locale-gen en
    sudo dpkg-reconfigure locales
    sudo nano /etc/default/locale
    psql
    sudo reboot
    psql
    ls
    mkdir itemcatalog
    git clone https://github.com/avandriets/ItemCatalog.git itemcatalog
    ls
    cd itemcatalog/
    ls
    python application.py
    apt-get -qqy update
    sudo apt-get -qqy update
    sudo apt-get -qqy install postgresql python-psycopg2
    sudo apt-get -qqy install python-flask python-sqlalchemy
    sudo apt-get -qqy install python-pip
    pip install bleach
    sudo pip install bleach
    sudo pip install oauth2client
    pip install requests
    pip install httplib2
    pip install redis
    sudo pip install redis
    sudo pip install passlib
    sudo pip install itsdangerous
    pip install flask-httpauth
    sudo pip install flask-httpauth
    python application.py
    psql
    sudo psql
    sudo mkdir /var/www/itemcatalog/static
    ls
    cd itemcatalog/
    git ststus
    git status
    git pull
    ls
    sudo rmdir /var/www/itemcatalog/static/
    sudo ls /var/www/itemcatalog/
    ln -s ~/itemcatalog/app/static/ /var/www/itemcatalog/
    sudo ln -s ~/itemcatalog/app/static/ /var/www/itemcatalog/
    sudo ls /var/www/itemcatalog/
    sudo nano /etc/apache2/sites-available/000-default.conf
    sudo apache2ctl restart
    ls /var/log/
    ls /var/log/apache2/
    sudo ls /var/log/apache2/
    sudo cat /var/log/apache2/item_catalog_error.log
    pwd
    nano item_catalog.wsgi
    nano item_catalog.wsgi
    sudo apache2ctl restart
    sudo cat /var/log/apache2/item_catalog_error.log
    nano item_catalog.wsgi
    sudo apache2ctl restart
    sudo cat /var/log/apache2/item_catalog_error.log
    pip list
    sudo cat /var/log/apache2/item_catalog_error.log
    nano item_catalog.wsgi
    sudo nano /etc/apache2/sites-available/000-default.conf
    sudo apache2ctl restart
    sudo cat /var/log/apache2/item_catalog_error.log
    nano item_catalog.wsgi
    mv item_catalog.wsgi wsgi.py
    sudo nano /etc/apache2/sites-available/000-default.conf
    sudo apache2ctl restart
    sudo cat /var/log/apache2/item_catalog_error.log
    nano wsgi.py
    sudo apache2ctl restart
    sudo cat /var/log/apache2/item_catalog_error.log
    ls
    sgi.py
    python wsgi.py
    nano config.py
    sudo apache2ctl restart
    sudo cat /var/log/apache2/item_catalog_error.log
    nano wsgi.py
    sudo apache2ctl restart
    nano config.py
    sudo nano /etc/apache2/sites-available/000-default.conf
    sudo apache2ctl restart
    nano config.py
    sudo cat /var/log/apache2/item_catalog_error.log
    sudo cat /var/log/apache2/item_catae
    sudo cat /var/log/apache2/item_catalog_access.log
    sudo cat /var/log/apache2/item_catalog_error.log
    sudo cat /var/log/apache2/item_catalog_access.log
    pip list
    pip install Flask
    pip
    pip install Flask --upgrade
    sudo pip install Flask --upgrade
    pip list
    sudo apache2ctl restart
    sudo apache2ctl restart
    nano app/ItemCatalog/views.py
    sudo apache2ctl restart
    sudo apache2ctl stop
    ls
    nano application.py
    python application.py
    sudo python application.py
    nano app/ItemCatalog/views.py
    sudo python application.py
    sudo apache2ctl restart
    sudo cat /var/log/apache2/item_catalog_error.log
    createuser
    sudo -u postgres psql
    sudo -u postgres createuser catalog
    sudo -u postgres psql
    psql -u
    psql --help
    psql -U catalog
    psql -U catalog -W catalog
    sudo nano /etc/postgresql/9.3/main/pg_hba.conf
    sudo systemctl restart postgresql.service
    sudo service postgresql restart
    psql -U catalog -W
    sudo nano /etc/postgresql/9.3/main/pg_hba.conf
    sudo service postgresql restart
    sudo -u postgres psql
    psql -d template1 -U postgres
    sudo -u postgres psql template1
    psql -d item_catalog -U catalog
    psql -d item_catalog -U catalog -W
    sudo nano /etc/postgresql/9.3/main/pg_hba.conf
    sudo service postgresql restart
    psql -d item_catalog -U catalog -W
    nano config.py
    sudo apache2ctl restart
    ls
    cd ..
    ls
    ls -al
    nano .bash_history
    sudo apt-get upgrade
    nano .bash_history
    nano itemcatalog/config.py
    sudo apt-get upgrade
    sudo apt-get update
    sudo apt-get upgrade
    ```

    - root's bash history
    ```
    ls
    pwd
    host
    exit
    cat /etc/apt/sources.list
    ls
    cat /etc/passwd
    adduser grader
    cat /etc/sudoers
    cat /etc/passwd
    cat /etc/sudoers
    ls /etc/sudoers.d/
    nano /etc/sudoers.d/grader
    sudo -u grader
    pwd
    login
    sudo apt-get update
    ```

3. Third-party resources that I used
    - [Postgre SQL site](https://www.postgresql.org/)
    - [Flask](http://flask.pocoo.org/)
    - [StackOverflow](http://stackoverflow.com/)
    - [SqlAlchemy site](http://www.sqlalchemy.org/)
    - [http://askubuntu.com/](http://askubuntu.com/)