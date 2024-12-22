# GET /role
> Use this endpoint to get information about a role.

### Query Needed
* `guildid` - Guild ID
* `roleid` - Role ID
### Parameters Needed
* None

## BDFD Example
````ruby
$httpGet[$getVar[apiURL]/role?guildid=$guildId&roleid=$mentionedRoles[1]]
$description[```json
$httpResult```]
````
**Result soon**