---
title: 'Setting Up an On Call Rotation'
published: 2026-01-15
draft: false
tags: ['oncall', 'devops', 'engineering']
toc: true
series: 'On Call for Developers'
---

There are likely an infinite number of configurations an on call rotation could have. The fun part is that it really depends on your teams needs and how much resources you are able to allocate.

## Responsibilities
It is important to first set some guidelines and boundaries on what a first responder is responsible for. Some options are:

- Take on interrupt work that would typically distract the team.
- Answer questions directed at the team.
- Monitor alerts and application health for anomalies and noise.
- Create playbooks and documentation.
- Respond to pages from automation or humans.

Many associate being on call with being available during off hours, which certainly could be part of the role. However, it can be beneficial to have an engineer who is on call the time to focus on reliability and shield the team from unnecessary interruptions.

If you're going from zero, I think starting small and only with expectations during work hours is a good introduction. Unless there is a need, you don't always need to have someone paged. Building up from there and ensuring your alerts provide the right signal for paging is an important first step.

## Scope
I've been on rotations where the scope was just what my team owned and I've been on rotations that were shared across an organization. Both have their pros and cons.

### Organization/multi-team

I loved the organization-wide on call because I got to work with people on other teams that I didn't typically work with. I also got a better view into what other teams worked on. Additionally, when you were on call you were truly separated from your day-to-day and could focus just on first responder tasks. There also were a large enough pool of people that it wouldn't be a frequent rotation.

However, when you were paged it was not often that it was something you were knowledgeable in or could assist with. Alerts would be tricky to diagnose if they were not in a stack you worked in frequently and getting help from the team could be tricky. 

There are times I miss this setup, especially with the cohesion it gave to our org. However, it is a very difficult setup to maintain and requires a lot of buy-in across your group. I don't think this is a great option for groups without existing on call practices

### Single team

Single team rotations are a lot simpler as you only need one group to be on board to make it happen. You also get to choose practices that work best for your team. I have really liked my current team's setup because I actually feel effective when I get paged. Context is a lot easier to chase down because there are less places to look for it. 

However, when it comes to issues that arise it can quickly turn into a game of hot potato to find the team that needs to handle that issue. Depending how large your team is, it could just be you alone with minimal support. It can be harder for other teams to get support if they have to know exactly which team handles a certain area.

## Length
Most rotations I've been on are a week long. Typically I've shared a rotation with 1-2 others so that it's only 8-12 hours that I would be primary. However there have been cases where I've been on 24 hour on call for an entire week.

Of course it's most optimal when you can share a rotation, especially if you can use time zones to your advantage. However, that's not always realistic and it's much more likely that you'll only be able to allocate one person to on call per week. If this is the case, there are options so that it doesn't lead to burnout which I'll discuss more in a future post.

I think the main takeaway here is that there should be clear expectations when you are on call and when you are off call. If someone is always listed as the primary in your pager app, then you don't really have an on call since that's not a realistic expectation for someone to be available 24/7.
