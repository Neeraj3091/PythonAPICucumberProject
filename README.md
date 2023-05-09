# PythonAPICucumberProject
Cucumber  -  Behave (python) framework

# > To solve this assignment I have selected Cucumber - Behave (python) framework
from the link :https://cucumber.io/docs/installation/

# > For installation of behave framework on local,
follow steps in link - https://behave.readthedocs.io/en/stable/install.html

# > Install bellow Packages from pycharm or cmd.
	1) api-testing -> pip install api-testing
	2) behave2cucumber -> pip install behave2cucumber
	3) pytest-bdd -> pip install pytest-bdd
	4) EnvFile -> pip install envfile 
	5) pytest -> pip install pytest

# > Setup API_KEY as environment variable -
create .env file in your root directory and enter below data :
	API_KEY="YOUR_VALID_API_KEY"
	API_KEY_WRONG ="ABCD1234"


#  Install on local -
 pip install python-dotenv

#  To execute the test cases use command
 behave 
 
 Note:
 To create a report :
 --> behave --format=json -o result.json

 To convert result.jason to Allure Report please find the below command.
 --> allure serve reports/
 
