# GET /message
> Use this endpoint to get information about a message

### Query Needed
* `messageid` - Message ID
* `channelid` - Channel ID
### Parameters Needed
* None


## BDFD Example
````ruby
$httpGet[$getVar[apiURL]/message?messageid=$repliedMessageID&channelid=$channelID]
$description[```json
$httpResult```]
````
![Results](https://media.discordapp.net/attachments/1065186079562534932/1072828646185766912/IMG_20230208_160732.jpg)