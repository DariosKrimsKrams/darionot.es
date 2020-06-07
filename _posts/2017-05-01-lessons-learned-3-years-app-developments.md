---
layout: post
title:  "Software-Developer lessons learned: 3 years app product-from-scratch development"
date:   2017-05-01 12:00:00 +0100
categories: blog
---

At Tiny Roar, my team and me developed a bunch of mobile games as apps as consultant. The conclusion can be separated into into four categories:

## 1. Features

* Bad planning: We built a lot of unnecessary functionality to begin with (like sprite animations, collisions, particle effects, flying objects, random movement) that we used only once. Instead we could have made other, existing features better and more complex. (Project: AlphaKlang)

* On every project programmers will develop more features than necessary. This is due to unfinished game design and gameplay. Most features will never see daylight, because while prototyping they still don't find usage, and if gameplay is ready to build in features, they no longer work, because of too little testing later in the development process. (Project: Glitch Force)

* Too much time was spent changing cycles and polishing, because we had no fixed deadlines. (Project: Jump the Rope)

* Overly-tight time estimations, or adding way more features than what was considered in the planning stage will cause your project to suffer. (Project: Crazy Maze)

## 2. Prototyping

* More prototyping: We used a technology for the first time. We also chose several libraries until we came to an agreement on which we wanted to use. This and the fact that we built our first prototype three weeks before finishing the project created some problems with trying to run the program outside the sandbox / debug build. (Project: AlphaKlang)

* Get better feedback: Build the prototype and let more friends, family and other players play your game. Then you will know exactly how to prioritise your further development tasks, and whatever isn’t featured you can leave. (Project: AlphaKlang)

* Wrong target audience, because of missing Testing. The look and feel were for girls and a younger audience. But the gameplay was really hard to play and maybe was mostly for boys and men. (Project: Jump the Rope)

* Do Testing and QA early in development cycle - approximately 50% of the time schedule for the first and a second versions were needed for this. Testing late costs time and money for changing or bugfixing features that were developed a long time ago. (Project: Sudden Strike Quiz)

---

## 3. User Feedback

* Show your game to friends and external users from day one. Get feedback from the very first prototype and from every further prototype. Do this especially to improve gameplay-relevant game design decisions like finding out what players like or dislike in the level design, or the challenges in finding the correct level difficulty. (Project: Crazy Maze)

* Develop your game design, level design and difficulty curve based on A/B testing. The balancing and gameplay prioritisation must be found together with the community of real users. It takes longer and is more cost- and time-intensive, but pays off by producing an even more polished product. (Project: Crazy Maze)

* After getting feedback (this sounds self-evident but is actually very hard to follow): Collect the tasks first, order them, create an offer and time schedule and do not begin developing until it's agreed upon by the whole team, the partners and you’ve received the final Go-ahead! (Project: Sudden Strike Quiz)

## 4. Craftsmanship

* More meetings: Start planning source code-review meetings at least every week if you work with two or more programmers. Also check the source code you use for more than one feature to optimise your programming-resources. (Project: AlphaKlang)

* Optimising for iOS devices was too late in the development process. (Project: Jump the Rope)

* Too little testing. Best case scenario: every week we tested gameplay, functionality and game design. (Project: Jump the Rope)

* Next time set aside more time to upskill and learn about the existing architecture and unknown source code from an already-built project, by our client, as well as learn the backend architecture which was already very overdone for a relatively small quiz app. Hosting was also surprisingly complicated to learn and work with for the first time. (Project: Sudden Strike Quiz)

* Updating 3rd party SDKs needed far more effort than expected - especially when we had to do it several times at the end of the project cycle. (Project: Sudden Strike Quiz)

* HTML5 for Games suck (Project: Elfer Liga)
