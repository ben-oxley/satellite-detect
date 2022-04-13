

## Installation instructions

### GDAL

GDAL installation requires binaries to be installed for the system before the python packages can be installed:

'sudo apt-get install awscli'
'sudo apt-get install gdal-bin'
'sudo apt-get install libgdal-dev'
'sudo apt-get install wheel'
'sudo apt-get install g++'
'sudo apt-get install python3-dev'
'export CPLUS_INCLUDE_PATH=/usr/include/gdal'
'export C_INCLUDE_PATH=/usr/include/gdal'
'pip install GDAL==$(ogrinfo --version | grep -o [0-9]\\.[0-9]\\.[0-9])'


## Useful links

https://aws.amazon.com/blogs/machine-learning/extracting-buildings-and-roads-from-aws-open-data-using-amazon-sagemaker/