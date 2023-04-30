#Set as environment variable

Set as an environment variable to not expose the API key.

The procedure for saving the API key as an environment variable in a Windows environment is as follows.

1. In Windows, environment variables can be set from System Properties. Search for "System Properties" from the Start menu and click on it.

2. When the System Properties window opens, click on "Environment Variables.

3. Click the "New" button in the "User Environment Variables" section.

4. In the "Variable Name" field, enter an appropriate name for the API key. For example, "API_KEY".

5. In "Variable Value," enter the actual value of the API key.


#Use API keys in your code

import os

api_key = os.environ.get('API_KEY')

Note:Windows environment variables are actually case-insensitive, 
which means that the variable name and the variable name in your code do not need to be an exact match in terms of capitalization. 
For example, if you set the variable name as "API_KEY" in the environment variables and reference it in your code as "api_key", 
the value will still be assigned correctly.
