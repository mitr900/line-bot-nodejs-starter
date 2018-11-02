# line-bot-nodejs-starter
starter point to create new line bot project

## How it work
Start express server to handle webhook from LINE

# Install
Clone and run
```
npm install
```
Modify `config.json`
```json
{
  "port" : "3000",
  "channelAccessToken": "fNo/YfJdyjbehXkDOQWfLn4GZHUO7Tc02opcIqXvn3bft60Yuqv4BHYtHVHEVROjfQw3ihYLT3Oz37TwFQ02R7NiyIC+bQkKb4EJXhB3nDqj9CtSMdqkgHsP0l8YLmAKSlSEUks2v4W6p2eS5HUoKwdB04t89/1O/w1cDnyilFU=",
  "channelSecret": "e96118e36074c1bc96818b2e3062179c
"
}
```
Run
```
npm start
```
then you can access [http://localhost:3000](http://localhost:3000)

Use [ngrok](https://ngrok.com/) to expose your local url
```
path/to/ngrok http 3000
```
config webhook url in developer console then enjoy your bot!

## Author
Sitthi Thiammekha
