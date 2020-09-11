[![CraigDoesData][logo]][link]

[logo]: ./logo.png
[link]: https://www.craigdoesdata.de/


# [Thing Finder](https://thingfinder.herokuapp.com/)

![Holla if ya hear me logo](/static/img/logo_t.png)

#### Project status - Complete


## Introduction

A [web application](https://thingfinder.herokuapp.com/) that allows the full [CRUD functions](https://en.wikipedia.org/wiki/Create,_read,_update_and_delete) of a database. The app allows you to add then name of a *thing*, along with its location. Then later, should you wish to *find* that *thing*, you simply open the app to discover where you left it.

This is of course not a particularly necessary use case, but I was more interested in getting to grips with the [Flask](https://flask.palletsprojects.com/en/1.1.x/) framework than coming up with a ground-breaking new app idea. The app works for the purposes of the learning exercise, but there are a couple of current issues with its functionality (see below) which prevent it from being effective in a real-life situation.

I followed [this tutorial](https://www.youtube.com/watch?v=Z1RJmh_OqeA) from [Jake Rieger](https://www.youtube.com/channel/UC0np-tFaO8GPJuIKZhwnQxg) on [freeCodeCamp](https://www.freecodecamp.org) to get to grips with Flask, and then went off-piste and added a few features of my own. Thanks freeCodeCamp! Thanks Jake!


#### Current Issues

The app does not currently support sessions, which means one database is shared by all users. This obviously limits its real-life effectiveness! I want to learn more about implementing sessions in Flask and allowing users to login so that they (and only rthey) can access their own items. That was beyond the scope of the tutorial I followed however, so I will get to it when I have a chance in the future.

As I am using the free tier of Heroku presently, the app is also not persistent over time. As Heroku shuts it down, it resets to its default mode and consequently loses all saved items. This also limits its real-life effectiveness. I don't currently plan to upgrade my Heroku tier, so this issue will persist for now.


### Technologies used
* [Flask](https://flask.palletsprojects.com/en/1.1.x/)
* [Flask SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/2.x/)
* [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)


## Contact
All feedback is warmly received. Craig Dickson can be contacted at [craigdoesdata.de](https://www.craigdoesdata.de/contact.html).
