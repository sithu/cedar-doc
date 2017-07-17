# Getting Started

## Run the application

Execute this server startup command in the same terminal that you installed the application.

`gunicorn --access-logfile - --log-file /tmp/prod-mgmt.log --bind 0.0.0.0:5000 --workers 4 --log-level info --capture-output run:app`

Example: 
```sh
(flask)~/app/prod-mgmt$ gunicorn --access-logfile - --log-file /tmp/prod-mgmt.log --bind 0.0.0.0:5000 --workers 1 --log-level info --capture-output run:app
```


