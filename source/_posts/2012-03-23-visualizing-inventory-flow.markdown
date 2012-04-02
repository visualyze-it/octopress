---
layout: post
title: "Visualizing Inventory Flow"
date: 2012-03-23 12:24
comments: true
categories: 
author: Guy Carpenter
---

Our [last blog entry](/blog/2012/03/15/merchandising-intelligence/)
ended with a discussion of this figure showing the deep seasonal discounting
patterns at Dolce and Gabbana.

<a href="/images/2012-03-15/dolce_gabbana_all_stock_discounting.png">
{% img /images/2012-03-15/dolce_gabbana_all_stock_discounting.png "Dolce & Gabbana - All Stock - Discounting" %}
</a>

{% pullquote %}
While this figure tells a in interesting story, it also begs more questions;
{"When is new inventory introduced?   Is discounted stock cycled back into non-sale inventory?"}
Our data is deep... we can answer these questions. 

To get a really complete picture of the inventory turnover we need to see the _flow_ of
inventory as it comes into stock, passes through discount stages, and eventually is discontinued.
This requires a flow diagram, a variation on an alluvial graph, which shows how stock items flow through the inventory.  Each dark band represents a measurement date.  Newly introduced stock funnels in at the top of the chart.  Full priced inventory is shown in blue, and sale items are grouped into streams below that, with pipes showing the flow of stock items between them.
{% endpullquote %}

Here's the Dolce and Gabbana data as a flow:

<a href="/images/2012-03-23/dolce_gabbana_all_stock_flow.png">
{% img /images/2012-03-23/dolce_gabbana_all_stock_flow.png "Dolce & Gabbana - All Stock - Flow" %}
</a>

It is really clear now is that there is very little flow from the sale inventory back into the full price inventory - a small exception is visible in the week of 16 December, but generally sale items are further discounted until they are eliminated entirely.

Comparing Merchant Patterns
===========================

We've already indicated that we believe 
Dolce and Gabbana have an atypically 
extreme inventory turnover pattern.
We can explore this directly using flow diagrams.
Consider the following major merchants:

Vince
-----

<a href="/images/2012-03-23/vince_inventory_flow.png">
{% img /images/2012-03-23/vince_inventory_flow.png "Vince - Inventory Flow" %}
</a>

You can see here that Vince makes heaviest use of the 60% discount range, and
fairly deep discounting from late January onward.  One interesting aspect
here is that there is absolutely no flow back up the levels.  Once discounted,
Vince products never return to a higher price category and _never_ return to full-price
inventory.

Park and Bond
-------------

<a href="/images/2012-03-23/park_and_bond_inventory_flow.png">
{% img /images/2012-03-23/park_and_bond_inventory_flow.png "Park_And_Bond - Inventory Flow" %}
</a>

Park and Bond moves significant stock into 70% band prior to Christmas, with deeper
cuts in mid-December.  Unlike Vince and Dolce and Gabbana, some stock does move back up
the scale, and a small percent of discounted stock eventually returns to full price.  However
most of the seasonally discounted items eventually end up heavily discounted in February
and discontinued.  By mid-February no discounted stock remains.

Williams Sonoma
---------------

<a href="/images/2012-03-23/williams_sonoma_inventory_flow.png">
{% img /images/2012-03-23/williams_sonoma_inventory_flow.png "Williams_Sonoma - Inventory Flow" %}
</a>

Unlike the merchants above, Williams Sonoma is primarily kitchen-ware and food items.
The flow diagram for Williams Sonoma doesn't reveal a strong seasonal discount cycle, but rather a sustained exchange of items through discount bands
and back into full-priced inventory.  This strongly suggests this merchant is using discounting
to stimulate sales rather than to turn over inventory.







