# post /channel/clone
> Use this endpoint to clone a discord channel.

### Body Needed
* `guildid` - Guild ID
* `channelid` - Channel ID
### Parameters Needed
* None

## BDFD Example
````ruby
$httpGet[$getVar[apiURL]/channel/clone?guildid=$guildId&channel=$channelID]
$description[```json
$httpResult```]
````
**Result soon**