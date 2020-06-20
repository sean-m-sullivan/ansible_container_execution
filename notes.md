##Commands used on fresh rhel 7.8
yum install python

subscription-manager repos --enable rhel-7-server-extras-rpms

curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py

python get-pip.py 

yum install python-virtualenv

virtualenv venv
