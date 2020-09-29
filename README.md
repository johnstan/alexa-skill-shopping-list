# Alexa Skill for the To-Do-List
This is the Alexa Skill companion for the [To-Do-List Server](https://github.com/paranerd/to-do-list).

## Prerequisites
1. You will need an Amazon Developer account as well as an AWS account
2. Clone the repository
3. [Create AWS credentials](https://developer.amazon.com/de-DE/docs/alexa/smapi/manage-credentials-with-ask-cli.html#create-aws-credentials)
4. Install the Alexa Skill Kit
    ```
    npm -i -g ask-cli
    ```
5. Configure the Alexa Skill Kit
    ```
    ask configure
    ```

6. Set the correct region (i.e. region=eu-west-1)
    ```
    nano ~/.aws/credentials
    ```

7. Set up config

    Rename config.sample.json to config.json

    Enter API URL and API service token 

8. Deploy
    ```
    ask deploy
    ```

## Language support
- German