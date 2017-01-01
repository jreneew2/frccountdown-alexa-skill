# frccountdown-alexa-skill
A simple alexa skill that you can ask how long until kickoff

# Setup

1. Create an Amazon AWS account. You can choose the free version.
2. Create a Lambda function in AWS and copy paste countdownlambda.py into the editor.
3. In the configuration tab:
    1. Set the runtime environment to python 2.7
    2. Set the handler to lambda_function.lambda_handler
    3. Create a custom role with the default options
4. In the triggers tab, create an Alexa skills kit trigger
5. Create an amazon developers account
6. Click on the alexa tab and crete a new alexa skill
    1. Choose the skill type which should be custom
    2. set the name, description, invocation name (I chose frc bot)...
    3. In the interaction model tab copy and paste intent-schema.json into the intent-schema section.
    4. In the sample utterances section copy and paste utterances.txt.
    5. In the configuration tab, select Lambda endpoint and copy and paste the ARN id into the feild.
7. You can test and save your skill. 
8. Done!

You should be able to test it by saying

"Alexa, ask frc bot how long until kickoff?"

or 

"Alexa, ask frc bot how many days until kickoff?"