# Sentiment analysis

Compass analyzes your message content to give each message a sentiment score, which can be either positive or negative. Under the hood, we use the [sentiment](https://www.npmjs.com/package/sentiment) module published on NPM to calculate sentiment.

<div class="alert alert-success">
  <p>
    As soon as sentiment score is calculated, we discard the message content. To respect privacy, we never store message content on our servers.
  </p>
</div>


## Coloring by sentiment

You can color-code people and channels based on message sentiment. For instructions on how to do this, [visit our guide on reading the map](/guides/reading-the-map.html#changing-map-settings).


## Leaderboards

The Nurturers leaderboard is a ranked list of those with the highest total sentiment scores. Total sentiment is calculated by summing the individual scores for each message over the given time period.


<span class="edit-link"><a href="https://github.com/kumu/compass-docs/blob/master/guides/sentiment-analysis.md" target="_blank"><i class="fa fa-github"></i> edit this page</a></span>
