---
{"dg-publish":true,"permalink":"/personal/blog-posts/goodbye-to-longtail-music/","noteIcon":""}
---

A few weeks ago I shut down Longtail Music and I wanted to spend some time thinking about it and writing my thoughts up on it along with talking about what I'm going to focus on next.

It had a run longer than many projects that show up on the internet, but everything ends, so I wanted to give a bit of a postmortem to talk about what I sent out to do, what it did, and why I think things never worked out.

I originally built Longtail Music as a spinoff from my time with The Bat Player, an internet radio client for the TV.  I thought if The Bat Player was a client for people who already love internet radio and know what they want to listen to, then I want to build something on the web for people to discover internet radio for the first time and discover a station they would love.

While this is the polished marketing elevator pitch it encompasses a lot of things that need to go right in order to pull it off.  Too many things.  So let's talk about them.

As a refresher, here's what Longtail Music was.

1. A discovery engine for people to find an internet radio station they would enjoy.
2. An internet radio client that displayed details about the artist including images and album information.  A smaller version of the player was also embeddable on external web sites.
3. A way to listen to previews and keep record of previously played tracks.
4. Provided links for each track so you can listen to it again on Spotify, Apple Music, YouTube, etc.
5. A crowd funding platform to allow stations to collect funds to help keep the station online.
6. A CMS for stations to post messages, update show schedules, announce special events, and contact fans.
7. A marketing interface for featuring the stations on social networks.
8. An analytics platform showing station owners the listening statistics and the most popular tracks.

That's a lot of functionality.

If that's everything I had to build, then just as many things were somewhat out of my control.  In order to run successfully, a handful of things had to work out.

### For Longtail Music to exist in any way the following needed to be true:

1) The stations have to be good.

This is obvious, but it's also not a given.  There are so many internet radio stations out there, and very few of them are worthy of featuring in front of people.

Most internet radio stations fall into the category of "Variety and misc".  An unappealing random grab bag of tracks.  It shows no personality, no target demographic, and no way for a potential listener to really dig in and know what is being offered.  Even the tag lines of these stations are all generic "From old to new, hard to soft, we have the best that music has to offer" or bragging about not sticking within a single genre.  So when I started Longtail Music I had the task ahead of me of trying to find stations that had a real personality and a clear goal.  A station that said things like "Promoting Soca and Calypso music to the world" was something that would catch my eye where "The best of 80s, 90s and today" would not.

Plus I'll be honest: I favored stations with fewer ads.  Ads are the worst.  Stations don't even make money off the ads, it just goes to whatever hosting company the server runs on.

2) The stations had to realize I'm just trying to help.

I'd email these stations individually.  And that is more difficult than it sounds as it would sometimes take a lot of digging to find out how to contact a station owner.  And if I got a response at all it would usually be along the lines of them assuming I'm scamming them, looking to sell them something, or are out to get them in some way.  I emailed hundreds of station owners and most of the responses were things like "I've been doing this for 15 years and I don't need you" or something equally negative.  Some stations even had concerns being listed next to another station on a web site because they thought they'd "lose listeners" and saw other stations as "competition" and didn't want to take part.

3) The stations had to be willing to minimally use the platform.

For each station I onboarded I would manually and painstakingly find their logo, audio streams, descriptions and misc station info and input it into the Longtail platform so the station owners didn't have to do anything to start using it.  I would ask if they ever changed their audio stream to make sure they change it on the platform, update their logo if they ever change it and update their schedule so people who drop by know what shows and content they're featuring.  This didn't really happen.  Many stations would get a new audio stream, not tell me, and not update it on Longtail, making their station completely unavailable.  So if I notice this happening I'd go digging for the new one, update it for them, and fix it.  This showed that the minimum effort of even making sure people can listen to their station was not being made by anyone other than me.  

But in general without stations that were actually using the platform nothing else mattered.  And that leads me to the next item.

4) The stations on the platform have to stay online.

Internet radio stations do not make money.  Each station owner operates at a loss and if they're lucky they'll have some donations to help each month.  But realistically the number of listeners most stations have can't make enough money even if everyone donated.  Because of this stations disappear, often.  There's only so much money people will spend on a hobby, and they just give up.  Out of pocket expenses, few listeners and increasing hassle with licensing leads to stations just being turned off.

5) I needed to get potential listeners to the site and discover these stations.

Even if the stations were on board and engaged that's only half the equation.  My goal was to spend some highly targeted dollars on advertising for stations on the platform in order to acquire new listeners.  Find people who like rap and send them to the rap stations, get country people to the country stations.  It's a self-identifying demographic and as far as targeting goes this seemed straightforward.


### What I wanted to provide for stations.

1. Stay in business: I wanted to give stations money.  For free.

Since stations need money to stay online I wanted to help on that front.  A part of Longtail was having a place that encouraged listeners to support the station via donations.  Donations were featured on the station's page and listeners could keep track of how much they've donated over time.  Much like Patreon, OpenCollective, or other crowdfunding platforms, I wanted to build a mutually beneficial ecosystem where it's super easy to donate to a station, and in turn the station gets to keep running and playing music for the listener.  I thought stations would really like this, since stations are asking for money _ALL OF THE TIME_.  They ignored it completely.


2. Get more listeners: I wanted to provide promotion of stations.  For free.

The whole point is to have people discover new music via internet radio stations, so acquiring users is important.  Plus In order to get donations you need listeners.  So you need to spend money to make money.  I wanted to spend marketing dollars, on behalf of the station, for free, to acquire them more users.  No catch, I just wanted more people to listen to their stations by routing them through Longtail Music.  But I wasn't willing to do this unless a handful of stations were at least minimally active on the platform.


3. A modern and more interactive listening experience: I wanted to build something that the "Facebook Generation" felt at home with.

Most internet radio stations have web sites that look like they were built 15 years ago.  Some of them were.  If you want new listeners then not only do the first impressions matter, but you have to keep them coming back.  People are used to newsfeeds, social posts and continued engagement.  Some of my favorite internet radio stations have live DJ sets, and with a single click of a button on Longtail a station can notify fans of the station via email that a live set is about to begin and it features that station on the home page so everyone knows a special event is occurring.  Stations never used this this feature, even when it notified people and featured the station on their behalf.


### What I wanted to provide for listeners

1. A simple way to discover an internet radio station to enjoy.

By clicking on genres you're into, or connecting your Facebook or Spotify accounts Longtail surfaced you a list of stations that were compatible with things you already listen to.  It was fast and easy to go from nothing to listening.

2. The ability to share your thoughts about songs and the station.

You could like and dislike songs, sharing with others what you thought about what was currently playing on the station.  You could also leave messages for other listeners and for the DJs.  These likes, dislikes and messages would then get emailed to station owners at the end of the week so they knew what people thought of the content on the station.

3. Showing you weren't alone, you saw other people, in real-time, tune in and react to songs.

As people tuned into the station, liked, disliked, or commented on songs, you would see it in real time.  This created a communial listening experience.  It wasn't just you listening by yourself, the world was listening with you.

4. A listening history so you can go back to that song you really enjoyed, and find it on your streaming service of choice.

You could look at your history to find that song you heard earlier, and quickly jump to it in Spotify or other services, to listen to it again or add it to your personal playlists.



### What went wrong

1. Not enough station engagement.

This has been mentioned a couple times, but building something for somebody who doesn't want it isn't going to get you anywhere.  It's still unclear why this happened, however.  Do they just not want the help?  Do they not want to have to remember to use another web site every day?  Do they think things are "good enough as it is"?  Are they afraid of being listed next to other stations and think it's "competition"?

2. Not enough listeners.

This is pretty common with anything new, you just don't have users yet.  But for me I wasn't willing on putting a ton of money into user acquisition until I felt confident that the stations would engage with them once they got there, and this never happened.  And with the promotion that did happen, my guess is people think "Spotify is good enough" and really aren't looking for another way to discover new music, so they're not jumping to press play on some random web site.

3. Zero stations asked for donations and zero users donated.

By "asked for donations" I didn't mean they didn't enable the feature, as it was on by default, but stations weren't telling listeners to donate via Longtail, or making posts saying they were accepting donations.  Therefore users didn't donate.

4. Onboarding each station was a chore.

It took _way_ too much effort to find, communicate with, and convince each station to take part.  I felt like a sales person who wasn't making money.  I even used a sales pipeline tool to keep track of who I emailed and what the status of each conversation was.  It's possible I spent just as much time emailing as I did with the development of the product.

The only way I'd do this differently is a fundamental change on how I think of the platform.  Add the station first without talking to them, and if they want to be involved later, then great, otherwise just leave it.  Maybe even just bulk import stations early on, regardless if they suck or not.  But I felt strongly about creating a relationship with each quality station, and that I was willing to put effort into it, even though it didn't pay off.

5. Aside from a cut of donations, there's no way to make money.

Simple as that.  But I wasn't trying to make money or build a business.  I just wanted people to hear some cool songs.  But down the road it would matter, since it always does.


### What worked

1. The idea was sound.

A few stations were active on Longtail Music, and seeing them post their schedule, send weekly updates to listeners, and keep their information active really showed me that the idea of the platform, when executed, was a really good one.

2. Putting a fresh coat of paint on internet radio does make internet radio more accessible.

Making people who feel at home on Facebook feel comfortable tuning into internet radio does modernize something that hasn't changed a lot for years.

3. I hired a designer and the end product came off pretty nice.

I made the choice upfront to have somebody design the site for me, and that was a good idea, though it slowed me down to have somebody else involved.  And while I had never built in React before, I built a pretty complex, multifaceted social platform with billing features.  It would have been easier if I built an iOS app or something, since that's my focus, the React app ran great for years.  I focused on performance, speed, and ease of use, and it worked.

### What I learned

1. Some people don't want your help & you can't make people care.

Even if you're just trying to do something helpful, for free, that doesn't mean that people want what you have.  A lot of these station owners have been doing it for many years and don't want anybody else involved.  Even if they need money, even if they want more listeners, even if their web page is crap.  It's their thing and they don't want you or anybody else involved.

I wanted to forge partnerships with people who care deeply about music, internet radio and sharing the worlds of both.  But making partnerships is hard, and you can't force somebody to care as much as you about your thing.  I cared about their stations, and I wanted to see them all thrive, but nobody cared that I cared.


2. Being a platform for other people's content is a difficult road.

Sometimes I think it would have been easier to create 100 of my own internet radio stations from scratch, operate them, and then use those stations on Longtail Music.  But I wanted to be a part of something bigger, and help people who really love music.  But anytime you're trying to surface the work and content of others you're at the mercy of other people.  Luckily I didn't have to pay to have this content on Longtail (unlike running a music streaming service like Rdio or a TV streaming service), so it didn't become a financial burden, but it's still a challenge when you don't control everything.  You rely on the people generating that content to be involved.


3. Building a product for the worst case scenario buys you time and lowers expectations.

I built Longtail Music knowing on day one there would be zero people and very little action on the platform.  So I made sure that every little thing gets surfaced in a stream and keeps the content fresh.  It was constantly showing the recent songs played by each station, and as each person tuned into a station it would show off that the station got a new listener.  Even at its most quiet the site had a feed of content that was always fresh, interesting and showed you what has been going on while you were away.  You could even discover new music just by browsing the home page and seeing stations that you might be interested in or cover art that catches you attention.  There were previews of recent songs, definitions of genres you might not be familiar with, and a way to discover stations via your Facebook and Spotify accounts.  I didn't build it to look good after hundreds of people started using it, I built it to attract somebody when nothing was going on and didn't require activity, and that was a good call.

In a similar vein, even though I talk about the lack of engagement by stations, I built Longtail Music to require as little usage by station owners as possible.  The platform would feature a station when it plays a song for the first time and keep a record of artists that are often played on the station so station owners don't have to do anything for it to be obvious what type of content they're playing.  It allowed the page for a station to always be up to date and featuring things without any human being involved.


4. Don't waste time building a user accounts system unless you need to.

Unless the value of the product relies on accounts to exist, it's a waste of time.  Longtail Music had user accounts where you could view your listening history, donation history, mark songs as favorites, like/dislike, etc.  None of this was necessary.  You could do most everything without a user account (on purpose), so I shouldn't have spent time building them in the first place.  That's not where the value of the product was.  It would have been a nice v2 addition if there were enough listeners and stations were active enough where they were generating content that should be pushed to individual users.


5. In general the scope of the product was too big.

I built it all, and it had everything I wanted, so it's not like the large scope had any real downsides other than it took longer to build.  But, like the user accounts, I probably shouldn't have started with the donations platform or any of the special features for station owners.  All of the dashboards and special station-owner features were probably never even looked at.  While seeing graphs about who's tuning in and when and what songs are popular are very cool, it's not terribly useful early on, and really not useful if the station owner isn't even logging in.

6. Don't spend time on all the dumb "social stuff".

I spent a lot of time working on integration with Twitter and Facebook.  Both from the automated posting standpoint, and using Facebook and Spotify data to match you up with stations via your social listening history.  I also spent a bunch of time on server-rendered pages for every part of the site so OpenGraph tags would render for anybody who linked to it.  None of this was required or helpful.

7. All the real-time interactive user stuff wasn't very useful with so few users.

While it was super cool to see, in real-time, users around you react to songs and tune into stations, it wasn't very useful, and it took a lot of work to build.


### What's next?

Nothing new, actually.  I'm currently working on an update for The Bat Player for AppleTV and I look forward to getting that out in 2020.  It's been a long time since I've worked on it, and it needs some updates.

Unlike social web sites where you require some critical mass before you can call yourself a success, a useful application is a success for each person who installs it and uses it.

So I'm going "back to my roots", if you will, and making sure the client for existing internet radio lovers is in good shape.

As far as the future, I haven't given up on the idea of introducing more people to internet radio and making it more accessible and modern.  I just don't know how to do it.  I'll keep thinking.  In the mean time I'll put on some good tunes and listen to internet radio somewhere else.
