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