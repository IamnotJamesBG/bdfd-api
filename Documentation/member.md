# GET /member
> Use this endpoint to get information about a member in a guild

### Query Needed
* `guildid` - Guild ID
* `userid` - The id of member
### Parameters Needed
* None


## BDFD Example
````ruby
$httpGet[$getVar[apiURL]/member?guildid=$guildID&userid=$authorID]
$description[```json
$httpResult```]
````
![Results](https://media.discordapp.net/attachments/1065186079562534932/1072827121610784809/IMG_20230208_160117.jpg)