---
layout: post
title: "Single Page apps"
date: 2013-12-24 11:16
comments: true
categories: [SPA,Code,Angular]
---
Single Page Apps or SPA's are all the rage and with good reason. About 3 years ago, I started to think about the idea and came to the conclusion that client machines have been putting on some weight in the last couple of years. We could no longer call clients "thin" and get away with it. 
<!-- more -->
Processing power on client machines have been increasing as per [Moore's law](http://en.wikipedia.org/wiki/Moore's_law) and the architecture of old was not really relevant anymore. Client machines could process data and deal with logic and business rules without the latencies involved when sending a request to the server for each button press or click on a dropdown.

![alt text](http://farm3.staticflickr.com/2250/2179201684_a5fe774379.jpg "Spaghetti")

My first attempts was a huge mess of spaghetti code, with all sorts of anti-patterns mixed in. Using [JQuery](http://www.jquery.com) to update the DOM an do Ajax calls to the backend. Anything more than toy projects and "hello world's" would be almost impossible to fathom. 

Then I discovered that people have been having the same problems and started to create frameworks and document best practices and even coining SPA as a term. I was in awe of all the possibilities available to me, I tried a few frameworks but did not have the time or patience to learn what seemed like an entire new language. So after failing to get to grips with the [backbone.js](http://backbonejs.org), syntax I discovered [Knockout.js](http://knockoutjs.com) and if only for a while I had nirvana!

Knockout.js was great it introduced me to the wonderful world of front development, it had some helped me structure my code in controllers and views and MVVM was great way to abstract and separate concerns it had 2-way data binding and all seemed good in my world. 

Well until I was once again stuck in a mess of spaghetti! I was starting to lose that in love feeling, the honeymoon period was drawing to a close. I went back and searched yet again to find something that would fit better, I just need to mention that Knockoutjs and Backbone.js are both great frameworks and I am sure had I more time and just stuck to it and learned any one of them, more thoroughly, I would probably be writing more about them. But when I met [AngularJs](http://angularjs.org) for the first time, it was love at first sight. 

![alt text](http://angularjs.org/img/AngularJS-large.png "AngularJS!")

It was and still is awesome, I work with it now on a daily basis and I am glad I had chosen it! My code is more structured, more functional and cleaner. By using directives and all the magic it provides like Dependency injection it is easy and "nice" to use it, objects are just plain objects no need to use an API to make special bindable objects. 

So for me SPA development starts and ends with angular it's a mature project with a clear direction and focus, it has a large and ever growing community and it's backed by Google, need I say more...
