# POST /attachment
> Send an attachment to a channel. Returns Message Object

### Query Needed
* None
### Parameters Needed
* None
### Body
* `channelId` - Id of the channel to add attachment
* `content` - Content for the attachment
* `name` - Name for the attachment

## BDFD Example
````ruby
$httpPost[$getVar[apiURL]/attachment;{
  "channelId": "$channelID",
  "content": "hello world",
  "name": "file.txt"
}
$description[```json
$httpResult```]
````
![Results](https://media.discordapp.net/attachments/1065186079562534932/1066268475091333190/IMG_20230121_133735.jpg)