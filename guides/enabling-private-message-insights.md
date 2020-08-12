# Enabling private message insights

Initially, Compass only access and analyzes messages in the public channels of your Slack team. We highly recommend turning on private message insights so that you don't miss valuable information about how your team is collaborating within private channels and direct messages.

<div class="alert alert-info">
  <p>
    Compass reads the contents of private messages in order to <a href="/articles/sentiment-analysis.html" class="alert-link">analyze sentiment</a> but we never store the contents of those messages, nor do we expose them to the rest of the team.
  </p>
  <p>
    We also never store the contents of public messages.
  </p>
</div>

To enable private message insights, click the settings icon in the lower left corner of the screen to open the admin interface.

![](/images/admin-icon.png)

In the **Insights** section of the admin interface, click the **Send Invites** button to invite your team to enable their private messages. 

![](/images/private-message-send-invites.png)

Compass will then send a message to every person on your Slack team, asking for permission to analyze their private messages:

![](/images/private-message-permission.png)

Each user will need to click the link in that message, then click **Authorize** on the next screen to let Compass analyze their messages:

![](/images/private-message-authorize.png)

After someone authorizes private messages, we will immediately analyze their private messages from the past quarter. From then on, we will analyze them in real time, as they are sent.

Once you've enabled private message insights, you can use the same **Insights** section of the admin interface menu to send reminders to anyone who hasn't enabled private messages yet. You can also see a list of those who have and have not yet enabled (in case you'd prefer to reach out on your own).

![](/images/private-message-send-reminders.png)

<span class="edit-link"><a href="https://github.com/kumu/compass-docs/blob/master/articles/enabling-private-message-insights.md" target="_blank"><i class="fa fa-github"></i> edit this page</a></span>


<!-- ## How we respect your privacy when analyzing private messages -->

<!-- Unfortunately, given the constraints of the Slack API, the only way for us to do even the simple, less intrusive calculations like "How many times have these two people messaged each other?" is to retrieve a data object that includes the content of those messages. So, even for simple analysis, our server still technically has to read message content.

As the documentation indicates, the only type of info we extract from the actual message text is @mentions and sentiment. When we analyze sentiment, we're calculating the positivity and negativity of individual words only—never analyzing full phrases that could convey more private meaning.

Also, we definitely never store message content on our end in any way. Content arrives at our server, we analyze it to build the stats and visuals you see in the app, and we store only the results of that analysis. -->