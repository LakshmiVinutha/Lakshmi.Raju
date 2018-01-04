# File Logger

## 1.	Objectives

The aim of this lab is to log chat conversations to a file using middleware. Excessive I/O operations can result in slow responses from the bot. In this lab, the global events are leveraged to perform efficient logging of chat conversations to a file. We will continue to extend the code from the previous lab.

````
{
  "type": "message",
  "timestamp": "2017-10-27T11:19:15.2025869Z",
  "localTimestamp": "2017-10-27T07:19:15.2140891-04:00",
  "serviceUrl": "http://localhost:9000/",
  "channelId": "emulator",
  "from": {
    "id": "56800324",
    "name": "Bot1"
  },
  "conversation": {
    "isGroup": false,
    "id": "8a684db8",
    "name": "Conv1"
  },
  "recipient": {
    "id": "2c1c7fa3",
    "name": "User1"
  },
  "membersAdded": [],
  "membersRemoved": [],
  "text": "You sent hi which was 2 characters",
  "attachments": [],
  "entities": [],
  "replyToId": "09df56eecd28457b87bba3e67f173b84"
}
````

