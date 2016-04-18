# System Design Question Bank

* Design an airport informtion kiosk system. A central authority would provide flight data - which has a cost associated. Interactive Kiosk/TV screens
  will be installed all over airports (consider multiple airports/multiple terminals). Justify your choices - first finalizing
  * requirements
  * constraints
  * system load
  This should help to provide an higher level system design. Based on interest of interviewer discuss further.
* Design a News Aggregator System - Like you are receiving a multiple input sources of news from different operators and  modes like blog, channels, telephone. We got to streamline and then push to customer as notification who is using our App. Scaling to million of requests, categorization, content push based on localization, NLP based on user history, etc...
* Various ways of designing a cache - multi - level layer cache to maintain different cache's and which can maintain different object and use different algorithms based on their usage. [Further reading](https://msdn.microsoft.com/en-us/library/dd129907.aspx#TemporalCache)
* Design Smart parking lot.
* WhatsApp search functionality.
* LinkedIn - Implement "How you are connected" feature.
  LinkedIn has this cool feature in which while visiting some user's profile, LinkedIn prompts how you are connecting to that user through the network.

  Assuming that the visitor and the profile owner are two nodes of a graph where the nodes represent users and edge represents friendship, a simple solution could be a bfs starting from both the nodes up to certain level and see if there are any intersections. The intersections would be the network link-nodes.

  Although this sounds neat, the problem is that in order to determine friends of each person, a separate DB query is needed. When the network goes deeper than 2 levels, it would be highly time consuming algorithm.  Is there a better efficient alternative? If not, how can we add better hardware support (parallel computing, grids, distributed database etc) in order to bring down the time required for computation?
  
  [Further Reading] (http://inviqa.com/blog/2009/09/07/graphs-in-the-database-sql-meets-social-networks)



