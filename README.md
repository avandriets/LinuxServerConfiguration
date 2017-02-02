# Linux Server Configuration.
Description for project Linux Server Configuration

1. Server IP address 35.160.201.101 SSH port 2200
2. URL to project site [Item Catalog](http://ec2-35-160-201-101.us-west-2.compute.amazonaws.com/)
3. Bash history
    - grader's user bash history
    ```
    **as root user**
    adduser grader
    ls /etc/sudoers.d/
    touch ls /etc/sudoers.d/grader
    nano /etc/sudoers.d/grader
    nano /etc/ssh/sshd_config
    visudo
    update
    apt-get update
    apt-get upgrade
    sudo locale-gen en
    sudo nano /etc/default/locale
    apt-get upgrade
    visudo
    sudo ls -a /etc/sudoers.d/
    nano /etc/ssh/sshd_config
    login grader
    dpkg-reconfigure tzdata
    sudo ufw status
    sudo /etc/init.d/ssh restart
    nano /etc/ssh/sshd_config
    sudo /etc/init.d/ssh restart

    **as grader**
    touch .ssh/authorized_keys
    mkdir .ssh
    touch .ssh/authorized_keys
    chmod 700 .ssh
    chmod 644 .ssh/authorized_keys
    nano .ssh/authorized_keys
    sudo ufw default deny incoming
    sudo ufw default allow outgoing
    sudo ufw allow 2200/tcp
    sudo ufw allow www
    sudo ufw allow ntp
    sudo ufw enable
    sudo ufw status
    sudo apt-get install git
    sudo apt-get install apache2
    sudo apt-get install libapache2-mod-wsgi
    sudo nano /etc/apache2/apache2.conf
    sudo apache2ctl restart
    python
    sudo apt-get install postgresql
    psql
    sudo -u postgres psql
    ls
    mkdir itemcatalog
    git clone https://github.com/avandriets/ItemCatalog.git itemcatalog
    ls itemcatalog/
    cat itemcatalog/item_catalog.wsgi
    git clone https://github.com/avandriets/ItemCatalog.git itemcatalog
    ls itemcatalog/
    cat itemcatalog/item_catalog.wsgi
    rmdir -rf itemcatalog/
    rmdir -r itemcatalog/
    rmdir -r itemcatalog
    man rmdir
    ls
    rmdir itemcatalog/
    rmdir -r itemcatalog/
    rmdir -R itemcatalog/
    rm -r itemcatalog/
    rm -rf itemcatalog/
    ls
    git clone https://github.com/avandriets/ItemCatalog.git itemcatalog
    cat itemcatalog/wsgi.py
    pip list
    sudo apt-get -qqy update
    sudo apt-get upgrade
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
    sudo mkdir /var/www/itemcatalog/static
    sudo mkdir /var/www/itemcatalog
    sudo ln -s ~/itemcatalog/app/static/ /var/www/itemcatalog/
    sudo pip install Flask --upgrade
    sudo nano /etc/apache2/sites-available/000-default.conf
    sudo apache2ctl restart
    nano itemcatalog/config.py
    sudo apache2ctl restart
    sudo -u postgres psql
    nano itemcatalog/config.py
    sudo apache2ctl restart
    ls itemcatalog/
    python itemcatalog/application.py
    sudo cat /var/log/apache2/catalog_error.log
    history
    cat .bash_history
    nano .bash_history
    ```

3. Third-party resources that I used
    - [Postgre SQL site](https://www.postgresql.org/)
    - [Flask](http://flask.pocoo.org/)
    - [StackOverflow](http://stackoverflow.com/)
    - [SqlAlchemy site](http://www.sqlalchemy.org/)
    - [http://askubuntu.com/](http://askubuntu.com/)