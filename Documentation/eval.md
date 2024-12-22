# POST /eval
> Use this endpoint to eval djs code through your bdfd bot

### Query Needed
* None
### Parameters Needed
* None
### Body Needed
* `code` - The code to eval

## BDFD Example
````ruby
$httpPost[$getVar[apiURL]/eval;{
  "code": "client.user.tag"
}]
$description[```json
$httpResult```]
````
![Results](https://media.discordapp.net/attachments/1065186079562534932/1072822714643009616/IMG_20230208_154404.jpg)