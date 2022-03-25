# TastyServerApp

A simple API for my TastyFrontendApp.
It mostly works as a middleman between the client app and the data. 

With that being said I did manage to write my own version of JWT just to avoid using Spring Security. 
Is it good? Most likely not. Was it more fun? It sure was.

I also implemented a few ideas to this project that I find really smart but simple. 
For example I disconnected the DB relationships - kept them in the table form so that they are easier to use in client app.
With that I was able to just send a Profile with list of posts ids and when client app loaded the post it just checked if its id was in said list.
