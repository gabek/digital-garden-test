---
{"dg-publish":true,"permalink":"/personal/blog-posts/owncast-plans/","noteIcon":""}
---

While I try to keep a public roadmap, and keep a reasonable plan for Owncast I rarely have an opportunity to gush about features I’m looking forward to building. So I thought I’d write a quick blog post to share some of my personal thoughts about the my vision of Owncast from a high level.

Owncast has been going through a large frontend refactor over the past year. And this wasn’t done lightly. It was done because I strongly felt if I wanted to build the features I had envisioned I wasn’t going to get there with the current frontend architecture, capabilities and tooling. So once this ships, I can get back to building features again! I’m really looking forward to that.

Admittedly I have some backend infrastructure refactoring planned once the frontend ships, but I do expect that to be more straightforward.

So what are these features?

The first big one I’m looking forward to are scheduled streams. The ability to say “I stream at 7:30 every Tuesday” or “This Friday I have an event at 6pm”. It will be a really nice thing to have on the Owncast stream page itself, so when you visit a stream that’s offline it tells you when you might want to come back. But that’s not the most interesting thing. People will be able to subscribe to a calendar so they have this schedule available to them wherever they are, so the real fans are always up to date. Additionally I can propagate this scheduled data to the Fediverse, updating the server’s profile info to include the next stream info, and inform followers that a stream is coming up soon. It’s all about informing people via different ways that something they might care about is coming up. I’m super excited about adding this functionality and I think it’ll benefit streamers and viewers alike.

Another feature I’m looking forward to is something I call “mini directories”. Something that people have asked for is to be able to run their own Owncast directories. The thought is that some communities and groups would like to be able to run multiple Owncast instances and have a way to link them all together. And while I’ve always thought that would be interesting, I’ve never been able to justify starting yet another rather large standalone software project that needs to be built, documented, supported, updated, etc for just a very small number of people. It’s not as simple as open sourcing the current Owncast directory site for many reasons.

So the solution I’m looking at is essentially every Owncast server to be a mini directory. Via ActivityPub (the standardized protocol that powers the Fediverse), each Owncast server will “Follow” other servers, and then the servers would federate between each other things like stream status (live/offline), schedule, and more. They could even list non-Owncast instances in their directory, as long as they are on the Fediverse. But of course they wouldn’t have all the additional federated info unless the remote server sent the required ActivityPub data. This means you could add PeerTube channels in your Owncast mini directory if you wanted to.

And because things like stream state will be federated between Owncast instances, you could essentially mimic a Twitch-style “raid” because once your stream ends it’ll know what other streams are currently live, and can recommend your viewers to check them out.

Cool, right? This will build upon the power of ActivityPub and shared, standardized specs. I hope this will expand some of the things we do with decentralized, federated data. In theory any Fediverse service could send the correct activities to Owncast and share state to show up in this directory (as long as the Owncast instance has explicitly followed the remote account, of course).

And while I could go on and on about ideas, I’ll briefly mention one more big one. A category of features I put under “replays”. I explicitly call them “replays” because that’s the point, for a viewer to be able to re-play part or whole of a stream.

The plan is to start with clips. And while that’s technically more challenging, with more UI and requirements from my side, I believe it has the most value. I think being able to share highlights of a stream will help grow people’s viewership more than entire streams, at first.

The entire replay project will be large, with a lot of design and UI requirements that admittedly I’m worried about. As I’ve blogged about in the past I’ve had a near impossible time getting design help, and it’s by far the skill set I have the hardest time with. So it’s going to be a long journey to get to where I’m trying to get to. But I’ll cross that bridge when I get to it.

Can’t wait to build this stuff. I hope some of you join me!