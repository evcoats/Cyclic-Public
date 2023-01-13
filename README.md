Project for automating the moderation of large-scale live-action games of "Assassins"

Django, AWS Elastic Beanstalk, JavaScript

Additional Discord bot in development for automatic collection of votes

http://www.Cyclic.Games

Hosted at The Bishop's School and UIUC

urls.py for REST API use is included below

```
curl --data "username=USERNAME_HERE&password=PASSWORD_HERE" http://cyclic.games/api-token-auth/
curl -X GET http://cyclic.games/gamesData/ -H "Authorization: Token TOKEN_HERE"
curl -X GET http://cyclic.games/getTarget/GAME_ID_HERE -H "Authorization: Token TOKEN_HERE"
curl -X GET http://cyclic.games/increaseScore/GAME_ID/PLAYER_ID/SCORE_INCREASE_AMOUNT -H "Authorization: Token MODERATOR_TOKEN_HERE"
```
