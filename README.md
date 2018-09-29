# orders-fee-distribution
Exploratory statistics and graphs on fee amount for more than 9,000 orders

Fee was adjusted for inflation and FeeInf was created. 9,393 orders included a fee.

The initial frequency distribution was highly positively skewed. An outlier analysis using inter-quartile range identified 71 outliers (comprising less than 1% of orders with fees ), ranging from $591 to $5,775.


After filtering out the outliers, the distribution became more normal, decreasing skew and kurtosis. However, the distribution contained major peaks at $80, $180, and $330, binned at steps of 10.

It was hypothesized that the type of the order, mostly characterized by the report form, ie the variable labeled Form, would reveal more about the three peaks.

The top four most frequent forms were selected, comprising 88% of the orders with fees. The FeeInf by Form values were binned and graphed in a stacked bar chart.
