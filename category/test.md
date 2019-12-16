---
layout: category
title: test
output:
  html_document:
    keep_md: true
---

Below is a quick graphical explorer of the **ACC**. Chromosome count graphs can be retrieved for either haploid (*N*) or diploid (*2N*) chromosome counts. All lineages with chromosome counts are listed below.

Please type any target lineage under the corresponding drop-down menu. Select at least one group, though multiple groups can be simultaneously selected. On a side note, data can be duplicated depending on the combination of lineages. For instance, if Chordates and Anura are selected simultaneously, data for Anura will be shown duplicated in the graph and descriptive statistics.


```r
library(DT)
datatable(head(iris), class = 'cell-border stripe')
```

<!--html_preserve--><div id="htmlwidget-db3fa3e831f31a9a219a" style="width:100%;height:auto;" class="datatables html-widget"></div>
<script type="application/json" data-for="htmlwidget-db3fa3e831f31a9a219a">{"x":{"filter":"none","data":[["1","2","3","4","5","6"],[5.1,4.9,4.7,4.6,5,5.4],[3.5,3,3.2,3.1,3.6,3.9],[1.4,1.4,1.3,1.5,1.4,1.7],[0.2,0.2,0.2,0.2,0.2,0.4],["setosa","setosa","setosa","setosa","setosa","setosa"]],"container":"<table class=\"cell-border stripe\">\n  <thead>\n    <tr>\n      <th> <\/th>\n      <th>Sepal.Length<\/th>\n      <th>Sepal.Width<\/th>\n      <th>Petal.Length<\/th>\n      <th>Petal.Width<\/th>\n      <th>Species<\/th>\n    <\/tr>\n  <\/thead>\n<\/table>","options":{"columnDefs":[{"className":"dt-right","targets":[1,2,3,4]},{"orderable":false,"targets":0}],"order":[],"autoWidth":false,"orderClasses":false}},"evals":[],"jsHooks":[]}</script><!--/html_preserve-->


