# Install Required Libraries for Stable-Baselines

https://stable-baselines.readthedocs.io/en/master/guide/install.html

`
sudo apt-get update && sudo apt-get install cmake libopenmpi-dev python3-dev zlib1g-dev
`

# Install Python version 3.7

https://www.folkstalk.com/2022/10/downgrade-python-3-8-to-3-7-ubuntu-with-code-examples.html

`sudo add-apt-repository ppa:deadsnakes/ppa`

`sudo apt-get update`

`sudo apt-get install python3.7`

# Create Python 3.7 virtual environment and activate it

`python3.7 -m venv venv`

`source venv/bin/activate`

# Install Python packages

`pip install stable-baselines`

`pip install tensorflow==1.15`

`pip install protobuf==3.20.*`

# From the root folder of the project install project package

`pip install .`

# Run test

`pytest -s`
