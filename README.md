# NYdock Runing the docker container
edit windows host file to add localhost.com with loopback address (C:\Windows\System32\drivers\etc\hosts) make sure to open as admin
clone the repo using git clone https://github.com/coolweare/NYdock.git
cd to cloned repo and navigate to the app dir
from the app dir run docker build -t app .
cd to nginx
from the nginx dir run docker build -t nginx .
cd to containerize dir and run docker compose up

