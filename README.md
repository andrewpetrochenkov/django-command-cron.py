### Installation
```bash
$ pip install django-command-cron
```

#### `settings.py`
```python
INSTALLED_APPS+=['django_command_cron']

# command_cron_worker.py settings
COMMAND_CRON_WORKER_SLEEP_INTERVAL=0.1
COMMAND_CRON_WORKER_RESTART_INTERVAL=3600
```
### Features
+   admin interface

### Management commands
name|description
-|-|-
`command_cron`|call pending commands once
`command_cron_worker`|worker

### Examples
```bash
$ python manage.py command_cron
$ python manage.py command_cron_worker
```

worker
```bash
$ python manage.py command_cron_worker
```

