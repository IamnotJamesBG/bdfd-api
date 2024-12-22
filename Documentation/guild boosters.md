# GET /guild/boosters
> Use this endpoint to get the list of all members who boost the server.

### Query Needed
* `guildid` - The guild id
### Parameters Needed
* None

## BDFD Example
````ruby
$httpGet[$getVar[apiURL]/guild/boosters?guildid=$guildID]
$description[```json
$httpResult```]
````
![Results](
https://cdn.discordapp.com/attachments/1055953726344540164/1076248294050758747/4tsika.png
)