# Network-Analysis
Network Analysis of Game of Thrones (Season 3)

Game of thrones is a widely popular television series based on the book series ‘A song of Ice and Fire’. It has an ensemble and is famous for building up characters and killing them off. Here, we try to analyze the interactions between these characters and identify the ones most central to the plot.

## The Data

We retrieve the network data from the github repo. This data was created from fan-generated transcripts. It contains two datasets, one with nodes and the other with edges. The nodes are the characters in the series and the edge weights define a metric for the interaction between these characters.

The interaction can be one of five types:
1.	Character A speaks directly after Character B
2.	Character A speaks about Character B
3.	Character C speaks about Character A and Character B
4.	Character A and Character B are mentioned in the same stage direction
5.	Character A and Character B appear in a scene together
