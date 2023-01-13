Project for automating the moderation of large-scale live-action games of "Assassins"

Moderators, players, and fans choose and vote on rulesets which maximize potential for game enjoyment

Django, AWS EB/EC2, JavaScript, React

Additional Discord bot in development for automatic collection of votes

http://www.Cyclic.Games

Hosted at The Bishop's School and UIUC

Initialized in 2019

urls.py for REST API use is included

```
curl --data "username=USERNAME_HERE&password=PASSWORD_HERE" http://cyclic.games/api-token-auth/
curl -X GET http://cyclic.games/gamesData/ -H "Authorization: Token TOKEN_HERE"
curl -X GET http://cyclic.games/getTarget/GAME_ID_HERE -H "Authorization: Token TOKEN_HERE"
curl -X GET http://cyclic.games/increaseScore/GAME_ID/PLAYER_ID/SCORE_INCREASE_AMOUNT -H "Authorization: Token MODERATOR_TOKEN_HERE"
```
