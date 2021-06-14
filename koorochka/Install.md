**Install Python 3.7**

`yum install gcc openssl-devel bzip2-devel libffi-devel zlib-devel`

`cd /usr/src`

`wget https://www.python.org/ftp/python/3.7.9/Python-3.7.9.tgz`

`tar xzf Python-3.7.9.tgz`

`cd Python-3.7.9`

`./configure --enable-optimizations`

`./configure --enable-optimizations`

`make altinstall`

`rm /usr/src/Python-3.7.9.tgz`

`python3.7 -V`
