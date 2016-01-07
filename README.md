#NorrisBot
scottyc/norrisbot

A Chuck Norris bot for Slack.

[`scottyc/norrisbot`](https://registry.hub.docker.com/u/scottyc/norrisbot/)

A big thanks to ['lmammino/norrisbot'](https://github.com/lmammino/norrisbot/) who actually wrote the app. I just Dockerized it.

##Running
```
docker run -d \ 
       -e BOT_API_KEY="<ENTER YOUR SLACK API KEY HERE>" \ 
       --name norrisbot \  
       scottyc/norrisbot
```