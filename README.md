# Laravel Nova Partition Metric Style Fix
Fixes the legend for parition metrics when more than 5 values appear.

--

In short, this package will turn this:

![Original Large](https://github.com/tylernathanreed/nova-partition-metric-style-fix/blob/master/docs/original-lg.png)

Into this:

![Fixed Large](https://github.com/tylernathanreed/nova-partition-metric-style-fix/blob/master/docs/fixed-lg.png)

Any results after the first 10 won't appear in the legend, but they will appear in the partition. Personally, I found that including more than 10 results caused too much noise to be useful, but only being able to cleanly show up to 5 results definitely wasn't enough.

## Installation (Using Composer)

```
composer require reedware/nova-partition-metric-style-fix
```
