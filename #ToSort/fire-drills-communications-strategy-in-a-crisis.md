# Fire Drills: Communications Strategy in a Crisis

_Captured: 2017-04-21 at 19:27 from [alistapart.com](https://alistapart.com/article/fire-drills-communications-strategy-in-a-crisis?utm_campaign=coschedule&utm_source=twitter&utm_medium=smashingmag)_

I once worked in a skyscraper in midtown Manhattan. Like in all large buildings, regular fire drills were routine. Every other month, the PA system would pop and emit a hiss of static, after which the bored, tired voice of someone in the building's communications room would announce that a fire drill was about to commence. The alarm would go off, the lights flash on, and nearly everyone would dutifully march to the emergency exits.

_Nearly_ everyone. Some of us, mostly those who'd worked there long enough to have been through this routine more times than we could count, would ignore the PA system--and the alarm, and the lights--and continue working. We figured we knew the routine, and so needn't go through the motions. But we were missing the point: the purpose of the fire drill wasn't to show us where we could find the stairwells (we knew!), nor to remind us not to take the elevators (of course!), nor to point out (again!) where the emergency phone was located. The exercise wasn't about transmitting information--it was about building muscle memory: we were directed to go through the steps often enough that they would become secondhand, something we could do without thinking. Which is _exactly_ the kind of experience you need should a real emergency take place.

Just as your office building needs a fire drill, your communications strategy needs an emergency plan. Every site or service will fail eventually; it's only a matter of when or how. An emergency communications strategy ensures you know where the exits are, when and how to take them, and where it's safe to assemble while the fire rages, so that you can act quickly and confidently--even under pressure. Most importantly, it guarantees that the tricky task of crisis communication can be handled effectively regardless of which member of your team is available: a fire _drill_ may be scheduled for 3:00 p.m. on a Tuesday, but an actual fire is much more likely to strike in the middle of the night, when the only one up is the lone engineer working late. At these moments, you are at your most vulnerable, but your users will expect you to perform with aplomb: enter the emergency plan.

## Imagine the worst

The first step to an effective emergency plan is also the most uncomfortable: you have to imagine everything that could possibly go wrong, from the most likely and least damaging, to the rare and catastrophic. Get your team together and take turns building a list of potential disasters. If you've dealt with these kinds of events before, you can start by retelling past stories of what went wrong. Be sure not to limit your discussion only to what has already happened, but everything that _could_ happen, too.

In generating these ideas, remember to consider potential sources of disaster that are both within and outside of your control. External dependencies--like a hosting provider's failing, or a power outage at your office--can have just as much of an effect on your site as an errant deploy or bug. And if your service extends beyond the web--say, if you're a local transportation authority--then you need to consider all the kinds of events that could affect the site; in that case, natural disasters, police activity, or accidents could all come into play. (Aside: these meetings can be depressing; pass around cupcakes to keep your team going.)

Once you have a great big list of nightmares, organize them across two axes: from most to least likely, and from most to least dangerous. Any event that is either very likely or very dangerous should get most of your attention as you craft your emergency plan; likewise, those that are rare and largely harmless get the least. Now you have a prioritized list of what you need to plan for.

![Figure 1: A map of possible disasters for a fictional transportation authority.](https://alistapart.com/d/fire-drills-communications-strategy-in-a-crisis/diagram.jpg)

> _Figure 1: A map of possible disasters for a fictional transportation authority._

Finally, work out as many possible mitigating circumstances for each of these events. You will not be able to envision every possible circumstance, as the very nature of a disaster makes it difficult to predict with that kind of certainty; but you can make some educated guesses about the kinds of things that might happen, based on past experience and your knowledge of your service.

For example, at Typekit (where I serve as Communications Director), one of the worst things that can occur is for our font network to be down. But a complete outage is exceedingly rare; we're more likely to experience an outage in a particular location (due to a local issue with our content delivery network). Understanding what those potential circumstances are allows us to craft smarter communication in the event itself. So, if our network is down in one place, we know we need to communicate the outage--while still reassuring our customers that the network is performing everywhere else.

## Assign roles

You've now identified everything that could possibly go wrong, and ranked those events accordingly; and you've eaten three cupcakes to get through it all. Now it's time to consider what happens when each of these events comes to pass.

In my Manhattan office building, each floor had two fire marshals assigned: volunteers from the building's tenants who agreed to act as point men in the event of a fire. Their job was to make sure everyone got out, call for medical help if needed, and direct emergency response personnel to the right locations. Everyone else could safely exit the building knowing that the fire marshals would take care of things.

Likewise, your emergency plan needs to have clearly assigned roles. Everyone needs to know what their responsibilities are at the onset, so the team can work effectively. At Typekit, we've identified three key roles that every emergency response requires:

  * **Firefighters**: The firefighters are the ones responsible for actually putting out the fire--they have to attend to whatever is broken and get it fixed, fast. In our case, that starts with our operations team, who can call in engineers if they need reinforcements.
  * **Communications team**: The communications team is responsible for communicating to the outside world during the crisis. They post to the status blog, respond to questions on Twitter, answer support tickets, and so on. They make decisions about who to communicate to, and how, from the onset of the crisis until it's resolved. Additionally, they decide on any follow-up communication that needs to happen; for example, in the case of a severe outage, they may decide to draft a detailed blog post explaining what happened, as well as our plans to prevent it from happening again.
  * **Messenger**: The communications team needs to understand the work the firefighters are doing, but the firefighters need to focus on getting things fixed rather than answering questions. Enter the messenger, whose job it is to liaise between the firefighters and the communications team, filling the latter in on the former's progress. At Typekit, the messenger is usually an engineer who eavesdrops on the firefighters' work, relaying critical information back to the communications team, and answering any questions they have. Importantly, the messenger needs to be familiar enough with the work of the firefighters to understand and effectively translate it back to the communications team. 

At a large company, you may assign several people to each role, so that in the event of an emergency, there is always someone to step up. (Remember: your worst disasters may happen at the most inconvenient times.) On a small team like Typekit, you may need people who are comfortable filling different roles at different times. For example, Typekit has only one person in charge of communications (yours truly), but in the event I am unable to attend to an emergency, anyone in the company is equipped to volunteer for the role. Likewise, any of our engineers may be called upon to serve as a firefighter or messenger.

In addition to defining roles, you'll need to consider how they work together. Who's woken up in the middle of the night when something goes wrong? How do you reach them? What if they can't be reached? Work out an internal system for rallying your team in the event of an emergency, and make sure everyone understands what is expected of them. Automated systems like [PagerDuty](http://www.pagerduty.com/) can take out the guesswork and make sure that _someone_ is available when needed.

Likewise, identify the circumstances under which everyone at the company needs to be informed of an emergency (whether they are participating in its resolution or not). The events which triggered the creation of an emergency plan at Typekit occurred last December, not long before the winter break. On a Saturday afternoon, when most of our team was out holiday shopping, an email thread was started to share a funny video about typography; a few of us were participating in that thread, when alerts started to come in that something was wrong with our font network. We shifted to address that, while continuing to converse in the same thread. Other members of the team peeked into their email that afternoon, glimpsed a busy thread on what appeared to be a frivolous topic, and went about their day unaware of what was going on. It took us the better part of an hour to realize the severity of the crisis, and call out individually for help from everyone who was available. That wasted our time (and that of our users); and it also resulted in mixed messages, as at least one member of our staff replied to a concerned tweet with inaccurate information. Since then, we've implemented the equivalent of a company-wide fire alarm: a [Yammer](http://yammer.com) account is set up so that any posts to it trigger an SMS message to everyone in the company. When a major event is identified, the first thing we do is post to Yammer to assemble the troops.

## Define a protocol

Now that everyone is in place, they need marching orders. During a crisis, tensions run high. Your customers may be upset or angry, and your team will be under a lot of pressure to get things fixed. It's _very_ important not to let any of this get to you, but to communicate in a manner that calmly reassures your customers that you are taking care of things.

A protocol defines what to communicate, across which channels, so that your communications team needn't waste time deciding how to handle a particular event. At Typekit, our protocol defines the communications strategy depending upon the severity of the problem (whether it affects the critical font network, or the less critical website), whether we've yet identified the cause, and how long before we expect it to be resolved. Given each of these factors, it then advises on how to communicate across each of our key channels:

  * our [status blog](http://status.typekit.com), 
  * support tickets,
  * email lists for our partners,
  * and our [blog](http://blog.typekit.com).

For example, any disruption to any of our services warrants an immediate post to the status blog; additional posts follow as we learn more or get closer to a resolution. If we don't have an immediate solution, we quickly respond to users on Twitter or via our support channel that we are working on it, and advise them to follow the status blog for the latest updates. Events which are wide-ranging or liable to affect a significant number of users will trigger a broadcast tweet to everyone who follows us. And any event that affects our partner systems may require an email alert to the operations teams at those organizations.

The protocol makes these kinds of decisions ahead of time, reducing the cognitive load on the response team during the emergency. Anyone who is called upon to handle communications can quickly refer to it to determine when and where they should respond. They do not need to think about who should be alerted or how, they can simply (and quickly) follow the path we've already defined.

Be sure to establish your channels thoughtfully: existing channels like your support system or Twitter account are obvious ones. Notification systems within your site or application are another. If you need to communicate when your site or service is down, consider a status blog (hosted on a completely separate system, so it doesn't succumb at the same time as your service). If you have several different systems, they may require unique channels. You may also consider adaptations to your site in the event of a problem: an alert bar that appears with important information, for example, or a feature on your homepage.

## Communicate appropriately

Of course, knowing _when_ and _where_ to respond does not tell you _how_ to do so. Communicating well is challenging under the best of circumstances, and it only gets harder during an emergency. It's important that you provide guidance for how to craft crisis communication so your team is supported when the pressure is high.

It's helpful to step back and remember why it is that we communicate in a crisis at all; crisis communication is intended to serve three key goals:

  * to share the facts of a situation, so your users understand what is happening,
  * to demonstrate what you are doing in response,
  * and to diffuse frustration.

This latter point is important: your users will be understandably annoyed (or worse) when your site or service is unavailable or otherwise impaired; good communication helps them know that you understand how they feel, shows that you have everything under control, and reassures them that you remain dependable despite the current state of affairs. How you communicate with your users during these events can have more of a lasting influence on them than any sunny day communique ever will.

As such, all crisis communication should:

  * Occur promptly, to show you're on top of things.
  * Be concise--meaning, brief but comprehensive. Crisis communication should be compact, delivering a lot of information in a small space and time.
  * Be as transparent as possible; perhaps more so than any other content you create, crisis communication must be honest and clear if your users are going to trust you to get through the event.
  * Clearly articulate what it is you are doing, and when possible, how long you think it will take. The latter can be difficult to estimate, so don't commit to a timeframe if you aren't sure of it; but if you know a solution is not imminent, it's best to be honest with your users about that fact.
  * Offer a sincere apology. Regardless of the source of the problem, you have let your users down; acknowledge this, and then get to work to make sure it doesn't happen again. 

Since you've already done the hard work to anticipate many of the things that can go wrong and the circumstances around them, you can use those scenarios and principles to craft example communication for your team to use. At Typekit, we have several canned status updates for events that affect the font network, so that anyone (even that lone engineer at 3:00 a.m.) can update the status blog in seconds with an accurate, clear, and appropriate post. Likewise, we have guidelines for appropriate tweets and support responses, including templates which any one of our team can use when needed.

One pattern for communication which I've found helpful in these situations can be defined in two parts: (1) what's up, and (2) what we're doing about it. Meaning, the first part of any crisis statement should identify what's up: what's broken, how it's broken, what that means for your users, and so on. The second part should clearly state what it is you are doing about it. This makes for reassuring communication in that you've acknowledged the problem, but also let your users know that you are working to fix it. So, a statement like "The font network is down in San Jose; we're working with our CDN partner to resolve it," is effective. While one that reads "Sorry, the font network is giving us trouble right now," does not; the latter makes it sound like you are bumbling through a problem, rather than taking charge of it.

Also consider adding a section to your style guide that notes how to adapt your language and tone in the event of an emergency. If your usual style is humorous or light-hearted, you may want to back off the jokes during a crisis, to communicate that you're taking things seriously. (And if you don't have a style guide, crisis communication is a good place to start one.) You may also want to cease other communication, to demonstrate you are focused on resolving the problem; turn off scheduled tweets or blog posts that could distract from that message.

Finally, make sure all this good guidance goes to use by locating it conveniently, so your team can find it in a moment's notice. A central location--such as an intranet--is a good start; if you have a status blog or other content management system, provide links from it to any documentation. Even better, provide an emergency dashboard with an easy-to-remember URL that your team can visit to find everything they need. In other words, everyone should know where to find the fire extinguishers.

![Figure 2: The admin screen of the Typekit status blog features helpful reminders about the purpose of crisis communication, links to our style guide and protocol documents, and templates for status updates.](https://alistapart.com/d/fire-drills-communications-strategy-in-a-crisis/status-blog.jpg)

## Review and revise

After a successful crisis (and yes, there is such a thing), pour yourself a drink. You handled an emergency well--quickly and accurately communicating, diffusing the tension, and delighting your users with your attention and concern for their needs. Bravo!

But wait: you are not done. No crisis is over the minute the site or service is back up. Now that you are no longer in emergency mode, it's time to look back at what happened and how you can do better.

If you're managing a service, you're probably already familiar with post-mortems after an outage. Post-mortems look at what happened during an event, asking hard questions about why it happened, if it could have been prevented, or if you could have handled it better. It's important that your communications strategy take part in this process. Look back at how your emergency plan worked and assess how things went. Did you respond quickly enough? If not, why not? Was your communication effective? Were your users satisfied with your responses, or did they grow more frustrated?

Don't wait for an emergency to review your crisis strategy; schedule regular reviews (say, every couple of months) to go over the plan as a team and assess if anything needs refreshing. Your systems may have changed since you put the plan into place, so that it's no longer optimized for you; you may have expanded into other markets, and need to similarly expand the channels you communicate across. You may have new staff members who bring a new perspective and questions to the process that you hadn't considered before. Hold these reviews like you would regular fire drills: even if you _think_ you know where the exits are, take a moment to walk down the hall with your colleagues.

## Relax

Perhaps the most difficult part of a crisis is the sense that you are not in control: everyone, from you to your users to the people working to put out the fire, will feel like they are at the mercy of someone or something whose behaviors they cannot completely dictate. Planning for an emergency provides a measure of equanimity in a disaster that allows you to work effectively, even while feeling like the universe is conspiring against you. And, just as importantly, it allows you to share that equanimity with your users, helping them feel confident in your abilities.

You will not be able to anticipate or plan for every disaster, but a little planning goes a long way. I was in that Manhattan skyscraper on the afternoon of August 14, 2003, when a blackout hit the entire Northeast, shutting down all of New York (and seven other states, plus much of Ontario). It took several minutes to realize the outage was widespread, and that the power was not likely to return soon. So, as we'd been taught, we headed for the emergency exits. Only here things didn't go quite according to plan: the backup system that powered the stairwell lights had failed, leaving the long walk down pitch dark. Some people on floors higher up discovered this before we did, and improvised: pooling a few penlights together, and aiming down the stairs, provided just enough light for people to slowly make their way down. The lesson? A good plan will get you 90% of the way through most crises, leaving you (and your users) in a good position to improvise the rest. And learn from it: in the weeks after the blackout, a new plan was made to replace the aging backup system and test it on the same schedule as the fire drills. So that the next time there's an emergency, there's one less thing to go wrong. No arguing with that.