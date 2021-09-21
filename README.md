# USER-AUTHENTICATION-USING-KEYSTROKE-DYNAMICS
Detection of an imposter trying to authenticate based on the his/her typing pattern of the password
## Working of Project:
* Typing patterns of users typing a same password will be recorded into a dataset
* The sets of timing features are extracted, which will be fed into user detection algo
* Step 1 -
    1. ML model will be trained with the keystroke patterns of the users
* Step 2 - 
    1. Test data with keystroke patterns of authorized and unauthorized users (imposters) will be provided
* Step 3 - 
    1. Model will be able to distinguish authorized users from imposters based on the test data
* Use of ONE-CLASS Support Vector Machine
    1. All the users are categorized as one category - 'Authorized', hence ONE-CLASS models will be required
