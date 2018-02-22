This will only work with ansible 2.3
To install, create a virtualenv and:
sudo rpm --install https://centos7.iuscommunity.org/ius-release.rpm
sudo yum -y install python36u-devel gcc libselinux-python
sudo pip3.6 install virtualenv
virtualenv --system-site-packages ~/ansible23
source ~/ansible23/bin/activate
pip install ansible==2.3.2.0 boto boto3 botocore awscli
