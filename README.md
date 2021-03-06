[![Build Status](https://drone.io/github.com/balasaajay/python_ops_automation/status.png)](https://drone.io/github.com/balasaajay/python_ops_automation/latest)
[![Code Climate](https://codeclimate.com/repos/574685975cb677008b005958/badges/228955a285fee4d82b97/gpa.svg)](https://codeclimate.com/repos/574685975cb677008b005958/feed)
[![Issue Count](https://codeclimate.com/repos/574685975cb677008b005958/badges/228955a285fee4d82b97/issue_count.svg)](https://codeclimate.com/repos/574685975cb677008b005958/feed)


# python_ops_automation

### python stop_redis_tomcat.py

Python script for Redhat based Linux OS for: 

1) Stopping redis, redis-sentinel and tomcat services if they are running

2) Removing redis package if it is already installed

To run this script execute command: ```python stop_redis_tomcat.py```

### verify_url_statuscode.py

Python script for getting status code of any URL and throw an exception if http connection code is an error code.
To run this script execute command: ```python verify_url_statuscode.py```

### ansible_syntax_check.py

Python script to run syntax check on a playbook. Before running this script, please update the path to your ```main.yml``` in the python file
To run this script execute command: ```ansible_syntax_check.py```
