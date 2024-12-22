# GET /listmembers
> Use this endpoint to get the list of members in a guild

### Query Needed
* `guildid` - Guild ID
### Parameters Needed
* None

## BDFD Example
````ruby
$httpGet[$getVar[apiURL]/listmembers?guildid=$guildID]
$description[```json
$httpResult```]
````
![Results](https://media.discordapp.net/attachments/1065186079562534932/1065567726040526858/IMG_20230119_151522.jpg)