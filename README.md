# Raspberrypi 4 Python and Node js installatnion
 
`sudo apt update && sudo apt upgrade`

# Python

`sudo apt-get install -y build-essential tk-dev libncurses5-dev libncursesw5-dev libreadline6-dev libdb5.3-dev libgdbm-dev libsqlite3-dev libssl-dev libbz2-dev libexpat1-dev liblzma-dev zlib1g-dev libffi-dev`

`wget https://www.python.org/ftp/python/3.9.0/Python-3.9.0.tar.xz`
`tar xf Python-3.9.0.tar.xz`
`cd Python-3.9.0`
`./configure --prefix=/usr/local/opt/python-3.9.0`
`make -j 4`

`cd ..`
`sudo rm -r Python-3.9.0`
`rm Python-3.9.0.tar.xz`
`. ~/.bashrc`


# NodeJS

`wget https://nodejs.org/dist/v14.17.0/node-v14.17.0-linux-armv7l.tar.gz`
`tar -xzf node-v14.17.0-linux-armv7l.tar.gz`
`cd node-v14.17.0-linux-armv7l/`
`sudo cp -R * /usr/local/`