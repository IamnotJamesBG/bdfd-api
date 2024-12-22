# GET /emojiinfo
> Use this endpoint to get information about emoji.

### Query Needed
* `guildid` - The guild id
### Parameters Needed
* `emoji` - The emoji


## BDFD Example
````ruby
$httpGet[$getVar[apiURL]/emojiinfo]
$description[```json
$httpResult```]
````
![Results](https://cdn.discordapp.com/attachments/1055953726344540164/1076248294050758747/4tsika.png)