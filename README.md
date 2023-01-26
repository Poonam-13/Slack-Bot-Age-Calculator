# Slack-Bot-Age-Calculator

Slack-Bot is a communication tool used by developers and companies to share information and communicate. It has grown very popular in recent years.

In this Golang project , we’re building a slack bot that calculates age. To calculate a person’s age in years we just have to take the difference 
between the current year and their birth years.

Connecting to Slack from Golang:

mkdir slack-bot

cd slack-bot

go mod init

go get -u github.com/slack-go/slack

go get -u github.com/poonam-13

Execute the program by running the main function:

go run main.go

Using the Slack Events API: The slack events API is a way to handle events that occur in the Slack channels. 
There are many events, but for our bot, we want to listen to the mentions event.
