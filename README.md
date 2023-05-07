# Slack-Bot-Age-Calculator 🖩

Slack-Bot is a communication tool used by developers and companies to share information and communicate. It has grown very popular in recent years.

In this Golang project , we’re building a slack bot that calculates age. To calculate a person’s age in years we just have to take the difference between the current year and their birth years.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)


## Installation ⚙️

1.Clone the repository:
git clone : https://github.com/Poonam-13/Slack-Bot-Age-Calculator.git

2.Connecting to Slack from Golang:

```mkdir slack-bot

cd slack-bot

go mod init ```


3. Install the required dependencies:

``` go get github.com/slack-go/slack

go get -u github.com/poonam-13 ```


4. Set up a new Slack app and obtain a bot token. You can create a new Slack app at [api.slack.com/apps](https://api.slack.com/apps).

5. Update the `config.yaml` file with your bot token.

6. Build and run the application:

``` go run main.go ```


6. Invite the bot to your Slack workspace and channel.

## Usage 🔥

1. In your Slack workspace, invite the bot to a channel by mentioning the bot using the designated bot username.

2. In the channel, you can use the following command to calculate the age of a person:

 ``` /agecalc [date of birth] ```
 ``` /agecalc 1990-01-01 ```
 
 
The bot will respond with the calculated age.

## Contributing ✨

Contributions are welcome! If you'd like to contribute to the project.

## Acknowledgements

This project utilizes the Slack API and the `slack-go` library. See the [Slack API documentation](https://api.slack.com) and [slack-go repository](https://github.com/slack-go/slack) for more information.

## 🔗Contact 📞

If you have any questions, feedback, or suggestions, please feel free to reach out:
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pooo13/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/Poooo_13)




