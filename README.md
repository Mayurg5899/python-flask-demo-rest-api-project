# python-flask-demo-rest-api-project
I have created a simple flask rest api creation project ,that will simply return a json object when we go to specified url (which has a view function with  post method attached to it).

Using Python Flask or ExpressJS, Write a REST API that reads the body and  returns JSON.


# API Method POST

# URL : /find_symbols_in_names


# Input JSON Body of the API:

{

    "chemicals": ['Amazon', 'Microsoft', 'Google'],

    "symbols": ['I', 'Am', 'cro', 'Na', 'le', 'abc']

}


# Output: display the chemical names with their symbol surrounded by square brackets:

{

    "result": ["[Am]azon, Mi[cro]soft, Goog[le]"]

}
