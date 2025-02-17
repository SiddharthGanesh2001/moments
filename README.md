# Installation - Setup for Moments

Clone the repo:

$ git clone https://github.com/SiddharthGanesh2001/moments.git

$ cd moments

$ git checkout generate-alt-tag

Create a virtual environment and activate it:
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

pip install -r requirements.txt
pip install --upgrade azure-cognitiveservices-vision-computervision


Create a .env file in the root directory and add the following from azure computer vision services:
endpoint="YOUR_ENDPOINT"
key="YOUR_SECRET_KEY"

# Setup for Azure for your private key and enpoint!
- Sign up for the a student account for Microsoft Azure: https://azure.microsoft.com/en-us/free/students/ – no credit card required

- Create an instance of the Computer Vision service and get an API endpoint of your instance of the service.

- Get a subscription key to authorize your script to call the Computer Vision API.

- Update the code with the endpoint and key and test it



Initialize and run the program:
flask init
flask run




NOTE: you can also use PDM to install dependencies and run the program, check out the readme file of the moments repository.

