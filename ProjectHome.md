# Problem Statement #
As theory and practice shows social networks ought to get a more and more important impact for the life of modern people. An unmeasurable amount of social networks exists within the World Wide Web, each one with its own social purpose, its advantages or disadvantages and it’s very special focus concerning aim and target group.  Deduced from all these networks people get not only confused by the variety but also overstrained by maintaining all their personal profiles. Besides it’s not always obvious, what network to use for a certain service; user initiated tasks (messages, blogs) are not available from each network, often services are liable to pay costs. Furthermore this effect results in multiple definitions of friendships with the same person in different networks without having any relation or correlation between them.
Another issue of current social network is the representation of social relationships between persons. Not only that most of the networks show lists of friends just in a tabular format without visual intuitive acquisition, also translative relations aren’t visualized in a clear and reproducible way.

# Approach #
The aim of this exercise is to develop an application to visualize social relationships of persons among various platforms. Persons are represented as nodes and connections between those nodes give information about their relationships. Furthermore the presence of a certain person within diverse networks shall be displayed and made clearly arranged.
To support various platforms the intended application is based on a multi layer visualization, wherein the user should be even able to aggregate one person’s accounts among several platforms to define one physical person out of it.

# Implementation #
The implementation of the application is ought to be based on the Java Programming Language. For the visual representation the visualization toolkit Prefuse (www.prefuse.org) will be used. As Java Applications are usually not able to be executed over the Web, additional technology is necessary. [Webstart http://java.sun.com/j2se/1.5.0/docs/guide/javaws](Java.md) not only allows us to execute an usual Java Desktop Application over the Http Protocol but also supports features like incremental updates and downloads.
For testing our application we will create XML based data (dummy data) of persons with relationships from various platforms.

# Graphical Visualization #
The following figures show the future functionality of the planned prototype. Figure 1 exemplifies the basic visualization of the different social network platform after the import of the XML (dummy) data. This visualization is ego-centered and the persons connected appear within their social network platforms. Obviously people appearing in different networks are displayed as doubles. The graph is network centered.

## Basic Network Centered View ##

![http://buddyfusion.googlecode.com/svn/trunk/unstable/buddyfusion/resources/hype_1.png](http://buddyfusion.googlecode.com/svn/trunk/unstable/buddyfusion/resources/hype_1.png)

After the import the prototype shall be able to suggest the merger of possible identical persons, as shown in next paragraph.

## Suggested Merger of Doubles ##

![http://buddyfusion.googlecode.com/svn/trunk/unstable/buddyfusion/resources/hype_2.png](http://buddyfusion.googlecode.com/svn/trunk/unstable/buddyfusion/resources/hype_2.png)

As a result of this suggestion the graph shows the social network of the user in a different and partly simplified way (next figure). Information on the social network platforms a certain person utilizes is visualized via multiple connections to one merged node.

## Partly Simplified Graph ##

![http://buddyfusion.googlecode.com/svn/trunk/unstable/buddyfusion/resources/hype_3.png](http://buddyfusion.googlecode.com/svn/trunk/unstable/buddyfusion/resources/hype_3.png)

According to the knowledge of the user of his personal network it shall be possible to merge all identical persons. Figure 4 presents the result of a manual merger of all identical persons. The focus of the graph is now adjusted to a more person centered view instead of a network centered view.

## Resulting Person Centered View ##

![http://buddyfusion.googlecode.com/svn/trunk/unstable/buddyfusion/resources/hype_4.png](http://buddyfusion.googlecode.com/svn/trunk/unstable/buddyfusion/resources/hype_4.png)
