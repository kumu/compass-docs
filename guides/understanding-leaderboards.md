# Understanding leaderboards


One of the ways we help your team improve how you work is through what we call “leaderboards” — ranked lists of the people on your team based on a variety of measures (anything from number of messages sent to complex SNA metrics like betweenness centrality).

To open the Leaderboards panel, click the list icon <i class="fa fa-list-ol">  </i> on the left side of the interface.

Just because someone is at the top of one of these lists doesn’t mean they are necessarily doing a good or bad job. Rather, these rankings are meant to serve as signals to help your team reflect and ask better questions.

There are healthy and unhealthy reasons why someone on your team might rank highly for any given leaderboard. You’ll need to dig deeper to understand the context behind a given ranking and how you might use that insight to improve your team.

![](/images/leaderboards.png)

Compass organizes your leaderboard metrics into three main categories: **structure**, **interaction**, and **behaviour**.

## Structure

#### Bridges

Bridges are the people who enable and control the flow of information across your team. These people are often highly connected or act as one of the few links between otherwise disconnected teams. This leaderboard is calculated using  [betweenness centrality](https://speakerdeck.com/jeffcmohr/social-network-analysis-made-easy?slide=40).

Many times the people on this leaderboard won’t surprise you. They’re your team leaders, executives, and the people who are always interacting in Slack. Pay special attention when someone shows up on this list you didn’t expect — it’s likely he or she is playing an essential but hidden role bridging across silos.

- Are the people on this list fostering collaboration and building new connections? Or are they creating bottlenecks?
- Do the people on this list feel overworked? Are they struggling to keep up?
- How might we incentivize and reward people playing essential yet hidden roles as connectors across the organization?

#### Influencers

Influencers are the people who can most quickly communicate with everyone across your team. They’re often centrally located, providing input and support to a wide range of people. This leaderboard is calculated using  [closeness centrality](https://speakerdeck.com/jeffcmohr/social-network-analysis-made-easy?slide=37).

These are the people to reach out to when you want to find out what’s happening across your organization. Since these people have the shortest path to all other people in your organization, they’re in a position to sense and spread information quickly (good or bad).

- Do the people on this list have a positive influence on your organization culture? Or are they spreading gossip and negativity?
- Are people being strategic about who they communicate with? Or are they collaborating with lots of people just for collaboration sake?

#### Insiders

Insiders are the people connected to other well-connected people on your team. They may not be highly connected themselves, but these people are often the influencers in a network. This leaderboard is calculated using eigenvector centrality.

These people often bring unique, cross-functional expertise that is valued by leaders across the team. Since eigenvector centrality incorporates the number AND quality of connections, these people aren’t always the most connected (but the connections they do have are with influential people).

- Do the people on this list message lots of people? Or are they connected to just a few key people?
- Are the people on this list highly valued and sought out by leaders in your organization? Or are they seen as people who “bother” others in your organization?

## Interaction

#### Collaborators

Collaborators are your connectors. They may not be the most active, but they interact with the greatest number of people in the team.

People on this leaderboard are often those engaged with people across many disciplines, tapping into diverse perspectives and expertise. They may also be the sign of an inefficient team structure, requiring many different conversations to get their work done.

- Do team members know who to turn to for help? Or do they have to talk to lots of people to get the information they need?
- Do the people on this leaderboard get a lot done each week? Or are they spending too much time networking across the organization?
- Do the people on this leaderboard hold roles where they should be talking to many people? If not, why might they need something from so many people?

#### Strong Ties

Strong Ties are the pairs of people who communicate most frequently. This leaderboard is measured by the number of interactions (@mentions or private messages) between two people.

Two people may end up as Strong Ties because they’re collaborating on an important project or filling a role which requires frequent communication. Or they might just be good friends!

- Are these people collaborating on work-related projects? Or is it a sign of procrastination, gossip, or lack of focus?
- Are teams structured in ways that enable the necessary communication for effective work? Or are people over-relying on a particular person for answers or support?
- Are teams over-relying on direct messages, missing opportunities for cross-pollination of ideas? Or do Strong Ties work out in the open?

## Behaviour

#### Chatterboxes

Chatterboxes are the people who send the most messages. This is calculated by the total number of messages sent.

These people may be deeply engaged and use Slack for the bulk of their communication. They may also be in a management role that requires lots of touch points with others.

Keep an eye out for those on this list that don’t seem to be getting much done.

- Are these people having conversations that are relevant to work?
- Do the people on this leaderboard get a lot done each week? Or are they spending too much time trying to keep up on Slack?
- Do these people feel the need to be “always on” and available through Slack? Or are they spending chunks of time away from Slack to focus on deep work?

#### Nurturers

Nurturers are the people who use the most positive language in their messages. This leaderboard is calculated by scoring the sentiment for each message and then totaling those scores.

Typically these folks are genuinely kind and caring — the members of your team that respect and are sensitive too other people’s feelings. Watch out for people on this list that may be covering up frustration with overly positive sentiment or withholding feedback.

- To what extent do these people inspire others and boost the overall morale of the team? Does their positivity feel authentic?
- Do the people on this list also offer critical feedback when needed? Or do they withhold feedback to avoid conflict?
- Does your team’s culture encourage people to be honest and direct?

#### Announcers

Announcers are the people who use announcements (@channel/@everyone/@here/@all) the most. This leaderboard is calculated by totaling the number of announcements made.

There are great reasons to use announcements, such as sending out company-wide updates or soliciting feedback from the team on a high-priority issue. However, using announcements to ask for help on trivial issues or share your new favorite giphy is not so great!

- Do we have explicit guidelines for how people should use Slack? Or are people spamming team members for non-essential items?
- Are people using announcements when they need help and don’t know who to ask? Or do they waste time reaching out to lots of people individually?
- Are people using announcements because they aren’t getting responses through other means? Does our team have a system in place
- Do we have an effective knowledge management solution in place? Or do people not know where to find information?

<span class="edit-link"><a href="https://github.com/kumu/compass-docs/blob/master/guides/understanding-leaderboards.md" target="_blank"><i class="fa fa-github"></i> edit this page</a></span>
