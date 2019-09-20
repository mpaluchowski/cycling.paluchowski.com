---
title: "Strava, What Are You?"
date: 2019-09-17T12:31:04Z
tags:
    - Strava
    - social networks
---

[Strava][strava] is having a crisis. They may not know it. They may even deny it vehemently, but it's clear that Strava does not know what it wants to be. The really cool features remain underdeveloped, the important, but missing ones, are neglected, while random stuff gets piled on top. Without focus they'll either sell out or shut down.

<!--more-->

I'm a [Strava Summit member][strava-summit], which means I'm paying for a bunch of extra features that I barely use. I am paying, though, so that they stick around because I generally like what they're doing. A number of their features are really useful, unique, and all of those are available for free. Plus, they're independent of any sports hardware vendor, so no matter what bike computer, watch or other gadget you are using, you can still have your data sync to Strava.

I wish they focused. I wish they built great features for their users instead of haphazardly seeking ways to monetize the platform. There's so much potential in there.

## What's good?

**The killer feature is matching people on the same ride.** We ride together and Strava shows me a list of all the other cyclists from my peloton (providing they recorded their ride, obviously). If I had a good chat with someone on the road, I can easily find back the person. It's automatic, it's reliable and it's great. Strava would've been worth signing up for even if it only had this feature.

On top of that there's [an experimental feature called "Flybys"][strava-flybys], which lets me check out people I passed on the way. Maybe someone had a fancy bike, or I hung onto someone's wheel and wanted to thank them later. Strava shows me all the people who crossed my path and where it happened. As with all experimental features, it's not fully reliable nor very easy to use, but pretty good nonetheless.

Then there's the **route editor**, better than any other I tried. There are apps dedicated to planning, storing and sharing bike routes, but none of them has an editor as efficient as Strava's. The map display is clean (if not particularly fresh[^1]); the editor chooses the exact routing very reasonably when I mark the next waypoint; rerouting is a simple act of dragging & dropping an existing route. I'm using Strava's editor for all my planning and afterwards manually export these routes to Garmin.

Finally, there's the **competitive spirit**---if that's your cup of tea. It's not mine, perhaps because I'm far, far away from the top ranks, but I do appreciate the concept. Every Strava club has a weekly rank list, every road segment too, with sublists for the men, women, age groups, years etc. Opening the profile of another athlete shows a comparison of your and their stats, ie. how your weekly average ridden kilometers compare. A *lot* of people live by all those rankings.

## What's *meh*?

Some features are a waste of space. **Athlete Posts** are the best example, [which I raged about previously][athlete-posts]. I've yet to see someone read or publish those.

**"Challenges"** sound like a good idea, but not the way they work right now. Most aren't challenging at all---any reasonably active cyclist can ride 100-150km in three weeks. Those are the ones that various brands pay for as a form of advertising. The in-house, monthly challenges of, say, doing a single 100km+ ride (a "Gran Fondo"), or doing a total of 1,250km in a month, are better, but hardly exciting. In the end, it's just a badge on your profile, and people seem to just mindlessly join the next month's ones without much enthusiasm.

## What needs more work?

A number of features are good beginnings that are begging for more attention from the product team.

First, communication around rides is all but missing. There's a simple, single-threaded commenting feature, where everything is public, and that's that. How about sharing photos between ride participants? Talking in private, among the group that rode together? Talking to a single person? What if I could schedule a ride with the same group for another day?

Clubs are a very fine idea, where people can schedule rides and talk. But the vast majority I saw are wastelands of activity. No events, no discussions, nothing. Strava should promote active clubs bury the deadwood. Help me find nearby clubs. If there's a public group ride nearby, I want to know about it. When I travel, I want to join club rides away from home too.

Then there's a list of running races. A *very* short one, because it's only two dozen events long with no way to add more. Why not develop it into a proper database? Add cycling races (and triathlons and others). Let people submit races, let those races promote themselves (charge them!), let Clubs schedule joint starts at races.

## What's missing completely?

There's no way to plan group rides outside of Clubs. I'd love to use Strava to schedule rides with my friends but we're not going to start a club just for that.

Support for different sports is limited to running and cycling. You can choose either of those as your "primary sport" in the profile, but what if you're an triathlete or swimmer? Either support these other disciplines in full, or drop them from the platform.

Routes created with Strava's editor can be browsed on one, long, paged, chronologically-sorted list. It's unusable for any amount larger than two pages. There's no way to filter the routes, ie. by length or region, no way to tag them as road, gravel or off-road. Why invest so much in the editor and neglect the storage?

Some people also argue that the mobile app should offer turn-by-turn navigation. [Strava is rejecting this long-standing request][strava-turn-by-turn] and maybe that's better so. Navigation is no easy business and better left to specialists in the field.

## Where will the money come from?

[As with any VC-backed business][strava-crunchbase], Strava aims at "monetizing" their user base, and either achieve profitability or sell out. Their current income streams are: special Challenges, brand-owned Clubs, and possibly branded Athlete Posts, but that's all advertising, and it always creates awkward incentives for the company. Their users become the product rather than customers.

They do offer the paid Summit, which consists of three feature packs. I found these only mildly useful, and judging by the number of people who are Summit members, most users concur. It's not about the money, because each pack costs less than a Starbucks latte.

I think **Strava would do better following a [model like Meetup.com][meetup]**, that is build excellent tools for organizing group events, then charge the organizers. I can see big sports brands, as well as local bike shops, creating their own Clubs and using the tools to stay in touch with their customers.

All this is nothing brilliant. Anyone who's an active user of Strava could come up with most of the above suggestions, and then some. I'm sure even Strava employees have these ideas. Why aren't they acting? I'm guessing that someone who's pulling the strings, a founder perhaps, is actively steering the service away from user-focused features and into wasteful efforts like Athlete Posts.

Whatever money Strava raised so far, it's not going to last forever, and I doubt their current activities are bringing in enough to cover all their costs. What I fear is that one day they'll announce that they're selling the service to someone like Garmin, which would either save them---if the buyer adopts the best features, develops them and drops the rest---or kill them---depending on who the buyer is and what motivates them. Time will tell.


[^1]: There are roads around Warsaw completed over a year ago, but Strava still shows these as "planned" or "under construction", even though OpenStreetMap is up to date.

[athlete-posts]: {{< ref "tech/strava-should-do-better-than-athlete-posts/index.md" >}}
[strava]: https://www.strava.com/
[strava-summit]: https://www.strava.com/summit
[strava-flybys]: https://labs.strava.com/flyby/
[strava-turn-by-turn]: https://support.strava.com/hc/en-us/community/posts/208836447-Turn-by-Turn-Audio-Notifications-for-Route-Navigation-mobile-
[strava-crunchbase]: https://www.crunchbase.com/organization/strava
[meetup]: https://www.meetup.com/pro/
