# User Manual

## Pre-requisites 

### Software requirements

* Although the application can run on any operation systems, this manual is target for Ubuntu Linux operation system.
* A reliable Internet connection on the server that you are installing.
* Either a static IP or dynamic IP assigned to the server.
* The network or router must allow TCP port `5000` for incoming traffic to the server.
* `python --version` - Check to see the server has installed Python 2.7.x.
* `bower --version` - Check bower package manager tool. 

### Hardware requirements

* Dual Core Intel or AMD CPU with 64-bit Architecture.
* 4 GB Memory.
* 20 GB SSD or SATA Hard Drive.
* Ethernet Port Network or Wifi

## Installation

Execute the following commands in a Linux shell Terminal.

* `ping www.google.com` - Ping to check the Internet connection. Press Ctl+D to exit.
* `mkdir app` - Create a `app` folder under the current user home path. E.g. /Home/User/cedar
* `cd app` - Go inside the app folder you just created.
* `git clone https://github.com/sithu/prod-mgmt` - Download the source code.
* `cd prod-mgmt/` - Go inside the prod-mgmt folder.
* `virtualenv flask` - Create a Python virtual enviroment.
* `. .env` - Load the virtual environment. Then, you should able to see `(flask)` at the beginning of the command prompt.

    Example: 

    ```sh
    (flask)~/app/prod-mgmt$
    ```

* `pip install -r requirements.txt` - Install all required Python PIP modules. At the end, you should see all the installed Python packages as below:

    ```sh
    Successfully installed Babel-2.4.0 Flask-0.12.2 Flask-APScheduler-1.4.0 Flask-Admin-1.5.0 Flask-BabelEx-0.9.3 Flask-Login-0.4.0 Flask-Mail-0.9.1 Flask-Principal-0.4.0 Flask-SQLAlchemy-2.2 Flask-Security-3.0.0 Flask-WTF-0.14.2 Jinja2-2.9.6 MarkupSafe-1.0 Pillow-2.5.1 SQLAlchemy-1.1.11 WTForms-Components-0.10.3 Werkzeug-0.12.2 apscheduler-3.2.0 blinker-1.4 click-6.7 colour-0.1.4 decorator-4.1.1 enum-0.4.6 funcsigs-1.0.2 futures-3.1.1 gunicorn-19.7.1 infinity-1.4 intervals-0.8.0 itsdangerous-0.24 passlib-1.7.1 python-dateutil-2.4.2 pytz-2017.2 six-1.10.0 speaklater-1.3 sqlalchemy-utils-0.32.14 tzlocal-1.4 validators-0.12.0 wtforms-2.1
    ````

* `bower install` - Install all front-end JavaScript and CSS libraries.








