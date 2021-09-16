
# Automatic Movie Streaming API for Dooplay (videospider alternative)
This is Dooplay auto embed script code with [superembed](https://www.superembed.stream) free movie streaming api.

### Download superembed player script!!!
In order to make this Dooplay auto embed work you first have to download se_player.php file from **https://superembed.stream**



## Dooplay 2.5.5 Auto Embed integration
Download files in this repository in dooplay/ folder and upload them to your wp-content/themes/ folder and rewrite all files.

Purge all caching systems on your website.

Now you will see a Multi Source option on your movie and episode detail page.




## Free Movie Streaming API for your website (without Dooplay) installation
You can also use just superembed API to show movies and episodes in iframe on your website if it is not Dooplay.


1. Download **[superembed player file](https://www.superembed.stream/#install)**.

Unzip it and upload it to the root of your website. You can rename the file or upload into subfolder but then you need to change the path and name accordingly in next steps.

2. Customize the settings. (optional)

You can change the look and behaviour of the player. Open the se_player.php file and change some variables. Everything is described inside the file.

3. Request the player.

Now that you have uploaded the player into your website you can start calling the player with parameters.

Request movie by IMDB id: https://yourwebsite.com/se_player.php?video_id=tt8385148
Request movie by TMDB id: https://yourwebsite.com/se_player.php?video_id=522931&tmdb=1
Request episode by IMDB id: https://yourwebsite.com/se_player.php?video_id=tt2861424&s=5&e=5
Request episode by TMDB id: https://yourwebsite.com/se_player.php?video_id=60625&tmdb=1&s=5&e=5

Paste these urls to iframe and the player will appear there.
For IMDB id you can use tt0000000 or just number 0000000.
For season and episode parameters you can use s=1&e=1 or season=1&episode=1.
Don't forget to always include &tmdb=1 if using TMDB id. 
## Acknowledgements

 - [Dooplay from Doothemes](https://doothemes.com)
 - [SuperEmbed free Movie Streaming API](https://www.superembed.stream)
 - [IMDB Movie Database](https://imdb.com)
 - [TMDB Movie Database](https://themoviedb.org)

  