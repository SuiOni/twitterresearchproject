# Introduction #

This project deals with the analysis of opinions in social media. In particular, it considers Twitter data and the statements regarding the most popular social TV shows in Germany. These statements are analyzed using state of the art natural-language-processing-methods and made available via a web interface.
The result can be viewed [here](http://lolcat.is.inf.uni-due.de:8080/).

Instructions can be found in our [UserGuidelines](UserGuidelines.md).

# Process #

The social media explorer uses a couple of steps to extract and visualize discussed topics with their sentiments. At first the [Crawler](Crawler.md) collects Tweets and stores them as JSON-files. The second step is the [Analysis](Analysis.md) that performs NLP-steps to create our data-format ClusterElements. Finally these ClusterElements are visualized through a web-interface. The process is illustrated in the figure below:
![http://www-stud.uni-due.de/~sfmiwoja/BilderFoPro/OverviewSocialMediaExplorer.png](http://www-stud.uni-due.de/~sfmiwoja/BilderFoPro/OverviewSocialMediaExplorer.png)

For further readings and a technical documentation look at the contents below:

# Table of Contents #

  * [Purpose of the project](Purpose.md)
  * [Data](Data.md)
  * [Architecture](Architecture.md)
  * [Setup](Setup.md)
  * [Crawler](Crawler.md)
  * [Analysis](Analysis.md)
  * [Visualization](Visualization.md)
  * [LimitationsOutlook](LimitationsOutlook.md)