# How We Work

## Cycles

We work in 6-week cycles at Basecamp. This fixed cadence serves to give us an internal sense of urgency, work as a scope hammer to keep projects from ballooning, and provide a regular interval to decide what we’re working on.

The idea is not that everything we ever decide to work on has to take six weeks or can be completed in that time. But rather that we think about how we can break big projects into smaller ones that can be done in that amount of time, and that we bundle smaller things into presentable scope of work that can be discussed.

On the product side, we’ve even formalized this further with the notion of Big Batch and Small Batch work. In Big Batch, we work on a single feature that’s likely to take the entire six weeks. In this mode, the six week limit works as a budget. If what we currently have in mind doesn’t fit within that, the first approach should be to judo the problem and scope hammer the domain. Most things we work on can fit within six weeks.

In Small Batch, we work on stuff that won’t take longer than 2 weeks at the maximum. So we can get more like 3-5 smaller things done in a single cycle.

But the general concept of the cycle extends to all departments. It gives us a regular rhythm to heartbeat on, and it allows us the patience to keep messing with the priorities for at least six weeks at the time.

In between each cycle, we usually spend 1-2 weeks cooling down, dealing with various backlogs or bug smashes, and figuring out what we should tackle next.

We’re currently naming the cycles after glorious mountains on earth and beyond.

## Heartbeats

It’s hard to keep up on what everyone is doing and what it means, if you just watch the stream of latest activity scrolling along in Basecamp. (It’s also a waste of time and source of stress to even try.) Instead, we have three chief mechanisms for keeping everyone in the loop about the work that’s going on. 

First, there’s the daily question of [What did you work on today?](https://3.basecamp.com/2914079/buckets/431372/questions/80177203), which supplies the nitty gritty details, but as a personal narrative. They’re a great conversation starter if you see someone working on something you either care about or want to learn more about. Please do use them as such!

Second, there’s the weekly question of [What will you be working on this week?](https://3.basecamp.com/2914079/buckets/431372/questions/61224583) which answers the nitty gritty at a slightly higher level. Well, at least the intentions of that!

Third, and finally, there is [the team updates](https://3.basecamp.com/2914079/buckets/431372/message_boards/61224577). They usually happen half-way through a cycle, at the end of a cycle, or when something new is launched. This is where the big presentation of work is done, and the main way for you to keep in the loop with what the company is focused on at a high, digestible level. 

## Pitches

Whether you work on the product development or not, your voice and observations can help determine what we should be working on. The way to exert this influence is through pitches. 

Write-up your idea of a new feature, a change to a feature, or any other product development you think we should be considering as a fully considered post (the more specific, the better). This gives the whole company a chance to consider and respond to the idea, and then we'll have the idea encapsulated in a post, available for reference at any time.

There'll always be more pitches than we have time to field, though. So it's important to have realistic expectations about what will happen after you posted your pitch. The default is simply that everyone involved with product development (and probably most everyone else in the company) will read and consider your pitch. That's a win right there. Even if the full pitch doesn't make it in, it can impact other product decisions by shining light on a weak point.

While a few pitches might instantly strike a chord loud enough to go on the plate for the next cycle, it's more likely that your pitch will sit for a while first. We're always working from a backlog of ideas and we have just a few things we can do every cycle, so chances are that even if everyone agrees the pitch is a great idea, it might not be the next most important thing for us to tackle. Don't be discouraged by this. We've had many pitches that have sat for many cycles, if not years, before finally coming together and then happening.

Jason, Ryan, and David is the team evaluating pitches for inclusion in the next cycle. Before the start of every cycle, Jason usually writes up a kick-off listing all the pitches that have been selected to be worked on.

## Asynchronously

We have people working all sorts of different hours and from all sorts of different places at Basecamp. That alone makes it hard to enforce a lot of tightly-coupled workflows during the day, but that’s a feature not a bug. Most of the work you do at Basecamp shouldn’t require you to be in constant communication throughout the entire day with someone.

It’s far better for everyone’s concentration and sanity if you collaborate as though most things will get an answer eventually, but not necessarily right this second. Your first choice of action should be to post a message, a todo, or a document about what you need to explain or need to know. Then others can read it on their schedule, when the natural lulls of the day allow it, rather than being interrupted right in their peak flow time.

Don’t take that as gospel, though. Some times you really DO need to tightly collaborate with someone for an extended period of time, and that’s fine. We have pings, hangouts, screensharing, or even in-person collaboration for when nothing else will do. (But most of the time something else will).

All that being said, you should still ensure that there is ample overlap with the people you work with most of the time. While most roadblocks can just as well be cleared in 15-30-60 minutes, they become real annoying if it’s a one-day turn-around every time.

In certain departments, like Support and Ops, it’s even more important that people are dependently available when they say they will be. That work has a lot of interrupt-based jobs that simply needs to be done right here, right now. So what applies to almost all work for design and programming and QA may well apply a little less frequently there.

## In self-sufficient, independent teams

Organizational theory is thick with descriptions of the trade-offs between functional and project company structures. We seek to be more project than functional. This means a single project team should be able to go from idea to deploy as independently as possible.

Thus, the fewer other departments a team has to pass through on their road to rolling out a new feature, the better. We should be working on opening all these natural road blocks that form by default when you have awesome, strong departments, such as SIP, mobile, Ops, QA, and so forth.

For example, a team working on a new scheduling feature should be able to test and integrate their work with the native apps without involving mobile, unless something special is needed. Mobile shouldn’t need a special heads up, and thus interruption and mental overhead or even guilt from lack of participation.

Similarly, a native feature that requires an API change should be carried out by that native team directly.

When we need to use the staging database, that should be self-service too. Have a script anyone can run to restore it. Don’t require going to ops and waiting around for someone to do it for us.

None of this means we can’t talk together or ask experts with more experience or expertise for their advice. It just means it shouldn’t be a required, necessary step to make Basecamp better.

As soon as organizational bottlenecks form, like a slew of features waiting for “the mobile integration”, we’re dragged towards more micro and detailed schedule management. It becomes a critical path with dependencies and making sure team Z is available just at the right moment for team A, such that nobody is blocked. That’s a poor fit for our organizational aspirations, so we have to work to counter that.
