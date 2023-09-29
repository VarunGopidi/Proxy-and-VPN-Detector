# Proxy and VPN Detector #
==============================================================================================

Given an IP address, the system will return a probabilistic value (between a value of 0 and 1) of how likely the IP is a VPN / proxy / hosting / bad IP. A value of 1 means that IP is explicitly banned (a web host, VPN, or TOR node) by our dynamic lists. Otherwise, the output will return a real number value between 0 and 1, of how likely the IP is bad / VPN / proxy, which is inferred through machine learning & probability theory techniques using dynamic checks with large datasets.

You required to install the following before running the Application:

1)Python -----> From https://www.python.org/downloads/  (version - Python 3.8.5)

2)Pip    -----> Using "sudo apt-get install python3-pip"(version - pip 20.1.1)

3)Django -----> Using pip install django-admin           (version - 3.2.4)

Open the base directory which have "env" in terminal and navigate to env/bin and use command "source activate" to start virtual environment.
Then get back to directory which have manage.py in it and run command "python manage.py runserver"
Note:do the above things in terminal/cmd and take care about versions.
