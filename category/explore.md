---
layout: category
title: Explore
---

Below is a quick graphical explorer of the **ACC**. Chromosome count graphs can be retrieved for either haploid (*N*) or diploid (*2N*) chromosome counts. All lineages with chromosome counts are listed below.

Please type any target lineage under the corresponding drop-down menu. Select at least one group, though multiple groups can be simultaneously selected. On a side note, data can be duplicated depending on the combination of lineages. For instance, if Chordates and Anura are selected simultaneously, data for Anura will be shown duplicated in the graph and descriptive statistics.


```{r}
install.packages(plotly) # if you haven't installed the package
library(plotly)

p <- ggplot(data = stops_county, aes(x = pct_black_stopped, y = pct_white_stopped)) +
  geom_point()

ggplotly(p) 


```
