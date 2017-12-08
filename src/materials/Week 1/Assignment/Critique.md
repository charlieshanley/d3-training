# Viz 1

## Notes
- line chart implies that x-axis represents time, or maybe something else continuous, but strategies appear to be categorical
- because there are two x-axes (mapping to separate things), vertical space does not map unambiguously to something
- configuration allows me to compare between products within strategy
- I'd like to see mean of all products for each strategy, and mean of all strategies for each product
- Unless strategies have a natural order (like chronological), should have sorted them by total amount
- Do we care about how sales strategy affects total sales? or sales for particular products? That'd affect design.

## Description of alternative
- Seems like primary goal is to display a continuous dv (total sales) as function of categorical iv (strategy)
- Secondary interest in how sales numbers break out between products
- Let's use bar chart where vertical dim is strategy, horizontal dim is sales $, products are stacked
- Sort strategies by total sales descending
- Sort products by mean sales descending
- Product key below


# Viz 2

## Notes
- comparison between totals of categories is prominent
- way too many colors to track
- Not sure what annotations represent
- no title; not sure what primary goal is here

## Description of alternative
- Uncertain of main priorities, so more artistic liberty
- probably want to communicate both size of markets and relative market share of participants.
- Squares whose area is market size, with inner square whose area is market share, in facet grid by market (horizontal) and company (vertical)
- Number/percentage annotations on mouseover


# Viz 3

## Notes
- On the left side, what property of the pumpkins is annual spending tied to? Not area. Width? What happened in 2009?
- A lot of different things going on. Maybe not focused enough.
- Many related quantities on lots of different axes/scales. Can they share them?

## Description of alternative
- Area chart where time is vertical, spending horizontal, time progresses downward
- Below that we have stacked bar of 2012 spending broken out into categories, sharing horizontal axis
- Comparing dollar amounts across years -- we should adjust for inflation


