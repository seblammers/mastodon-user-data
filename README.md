# mastodon-user-data
A dataset covering the hourly increase in mastodon users from 2018-08-12 to 2022-11-07.  

Data was kindly provided by Zoltán Gálli, who runs the Mastodon Users Bot at https://bitcoinhackers.org/@mastodonusercount.

Note that this dataset is a snapshot that is not continuously updated. The bot continues to publish the latest stats on an hourly basis.

### Data Dictionary

# `mastostats.csv`

| variable       | class  | description               |
|----------------|--------|---------------------------|
| timestamp      | double | Unix timestamp            |
| usercount      | double | total number of users     |
| instancecount  | double | total number of instances |
| tootscount     | double | total number of toots     |

### Data collection
If you want to learn how exactly the data was collected check out the source code for the bot at https://github.com/gallizoltan/usercount.

