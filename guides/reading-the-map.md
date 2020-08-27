# Reading the map

The star of the show in Compass is the **map** of your team.

On the map, each circle represents either a **person**, a **Slack channel**, or a **response**-to-a survey question. Each line , represents a relationship between two people, a relationship between a person and a channel, or a relationship between a person and a survey response.

You can use the toolbar in the top right of the map to select **People**, **Channels**, or **Surveys**, changing the type of relationships that Compass displays on the map.


## People

In the **People** view, Compass connects people based on Slack @mentions and, if you have [enabled private message insights](/guides/enabling-private-message-insights.html), direct messages between people. Use the slider at the bottom of the map to adjust the threshold for how many @mentions or direct messages Compass requires before drawing a connection.

![](/images/map-people.png)


## Channels

The **Channels** view connects people to the Slack channels they post to. Use the slider at the bottom of the map to adjust the threshold for how many posts Compass requires before drawing a connection.


![](/images/map-channels.png)


## Surveys

If you've run a few [surveys](/guides/running-surveys.html) in Compass, you can visualize that data, too.

Click on the settings icon <i class="fa fa-sliders">  </i> in the toolbar at the top right, then use the **Source** dropdown to toggle on connections from any surveys you have run.

![](/images/map-surveys.png)

In the **Surveys** view, Compass behaves differently based on the nature of the survey question.

If the survey question's possible answers are other people in the workspace, Compass will connect people to people based on their responses. For example, the question "Who did you most recently ask for advice?" would offer other workspace members as the possible answers, and Compass would connect people based on their responses.

If the survey question's possible answers are more generic, Compass will connect people to their responses. For example, if you send a survey asking "What skill are you most proud of?" and offer a list of skills, Compass will connect people to the skill(s) they chose.


## Changing map settings

In all three types of Compass maps, you can customize the visualization using the toolbar in the top right.

With the time range dropdown, you can choose the time period that Compass takes into account when it draws the map.

If you click the settings icon <i class="fa fa-sliders">  </i> in the top right toolbar, you can access additional options. Aside from the **Source** tool that you can use to bring in survey data, you can also apply color-coding, or include only certain people in the map.


<span class="edit-link"><a href="https://github.com/kumu/compass-docs/blob/master/guides/reading-the-map.md" target="_blank"><i class="fa fa-github"></i> edit this page</a></span>
