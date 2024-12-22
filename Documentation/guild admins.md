# GET /guild/admins
> Use this endpoint to get the list of all members who have administrators permissions.

### Query Needed
* `guildid` - The guild id
### Parameters Needed
* None

## BDFD Example
````ruby
$httpGet[$getVar[apiURL]/guild/admins?guildid=$guildID]
$description[```json
$httpResult```]
````
![Results](
https://cdn.discordapp.com/attachments/1006603996976386158/1076188772749815859/image.png
)