# get /channel
> Use this endpoint to get information about a guild channel

### Query Needed
* `guildid` - Guild ID
* `channelid` - Channel ID
### Parameters Needed
* None

## BDFD Example
````ruby
$httpGet[$getVar[apiURL]/channel?guildid=$guildId&channelid=$channelID]
$description[```json
$httpResult```]
````
**Result soon**