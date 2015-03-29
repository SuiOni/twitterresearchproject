# OrthographicCleaning #

In order to detect mispelled words that describe the same concept we used this processing step. It uses the Levenshtein distance to calculate similarity between the words and assigns the most frequent spelled form to words with a similarity > .7.
It operates just on tokens that are annotated with a "simple Sense" (s. [Analysis](Analysis.md)).

The figure below shows words with a similarity > .7 in a graph:
In the shown example all the words would be assigned with "Regelungen" (German for "regulations").

![http://www-stud.uni-due.de/~sfmiwoja/BilderFoPro/OrthographyCluster.png](http://www-stud.uni-due.de/~sfmiwoja/BilderFoPro/OrthographyCluster.png)
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