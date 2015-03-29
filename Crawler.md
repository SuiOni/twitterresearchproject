To collect some sample Tweets we have written a Crawler using the [Twitter4J](http://twitter4j.org/en/index.html) library. The Crawler is a simple server-side application which listens to the Twitter stream and saves the incoming Tweets on certain Hashtags as a JSON file. Because our main goal is to analyze Tweets regarding shows that go on TV in a weekly turn the Crawler groups the crawled Tweets by week which means at the end there is one JSON file per Hashtag per week, which goes into the [Analysis](Analysis.md). The Crawler can be configured manually by the user which means the user can add or delete Hashtags on which the Crawler listens (s. [UserGuidelines](UserGuidelines.md) for more).
<br />
<br />
## read more ##

  * [Purpose of the project](Purpose.md)
  * [Data](Data.md)
  * [Architecture](Architecture.md)
  * [Setup](Setup.md)
  * [Crawler](Crawler.md)
  * [Analysis](Analysis.md)
  * [Visualization](Visualization.md)
  * [LimitationsOutlook](LimitationsOutlook.md)