# GET /user
> Use this endpoint to get information about an user

### Query Needed
* `userid` - The id of member
### Parameters Needed
* None


## BDFD Example
````ruby
$httpGet[$getVar[apiURL]/user?userid=$authorID]
$description[```json
$httpResult```]
````
![Results](https://media.discordapp.net/attachments/1065186079562534932/1072829401307299870/IMG_20230208_161046.jpg)