---
layout: post
title: "Data Mining for Merchandising Intelligence"
date: 2012-03-15 17:04
comments: true
categories: 
author: Guy Carpenter
---

Here at visualyze.it we have developed a really interesting data-set tracking the price history
of tens of thousands of products from high-end merchants like Barneys and Saks.  The
data covers apparel, jewelry, beauty products, homewares and food items.
This gives us a unique ability to analyze trends across many different market segments, merchants and
brands.

Let's talk about boots for men.

<a href="/images/2012-03-15/mens_boots.png">
{% img /images/2012-03-15/mens_boots.png "Mens Boots" %}
</a>


The visualyze.it price history data tracks the price fluctuations of several hundred pairs of men's boots
available from the major high-end retailers.  The figure below shows raw product
price vectors for December 2011 and January 2012.  Each line represents the trajectory
of the price of one product.

<a href="/images/2012-03-15/mens_boots_product_price_vectors.png">
{% img /images/2012-03-15/mens_boots_product_price_vectors.png "Mens Boots - Product Price Vectors" %}
</a>

You can click on the graph to view it in full detail, but you know it's still 
pretty much impenetrable; I'm including it to give you feel
for the depth of the raw data set.  Even in this dense forest of data
it is obvious that something interesting is happening in the pre-Christmas period;
prices drop very suddenly.  A few of the most expensive items are discounted
3 successive times in December.

So let's dig a little deeper and see what more we can learn.
The figure below charts the mean price price of men's boots by brand over a full year.

<a href="/images/2012-03-15/mens_boots_mean_price_by_brand.png">
{% img /images/2012-03-15/mens_boots_mean_price_by_brand.png "Mens Boots - Price Trend by Brand" %}
</a>

There are two things that show clearly here; that boot prices are highly stratified by brand, with top-end brands like Rick Owens, Ann Dumeulemeester and Bruno Cucinelli commanding double the price of their competitors, and that men's boots are fiercely discounted in the Christmas season.

The degree of discounting for the high-end brands is impressive - around 50% mean price drop.  It would
be interesting to look at the price by merchant to see if specific retailers are
driving this discounting.  The following figure shows the mean price for a pair of men's boots at
a number of major high-end retailers over the course of year.  Click to view full size.

<a href="/images/2012-03-15/mens_boots_mean_price_by_merchant.png">
{% img /images/2012-03-15/mens_boots_mean_price_by_merchant.png "Mens Boots - Mean Price by Merchant" %}
</a>

You can see here that the seasonal price variation for men's boots at Barneys and Dolce & Gabbana are quite severe.  No so with Gorsuch, Saks and Park and Bond.  

The Dolce & Gabbana pricing really extreme, and worthy of a bit more exploration.  This next figure is
a bit more complicated, but you've come this far, so stick with me.  For this figure I've included the entire stock 
range from Dolce & Gabbana, not just men's boots.  Since we maintain a long-term price history
on all of the products we track, we can easily determine the "standard price" for any item, and so 
compute the discount rate for any point in time. 
The graph below shows the number of products (reflected by the size of each circle) at each 
discount level over the course of the last year.

<a href="/images/2012-03-15/dolce_gabbana_all_stock_discounting.png">
{% img /images/2012-03-15/dolce_gabbana_all_stock_discounting.png "Dolce & Gabanna - All Stock - Discounting" %}
</a>

This figure gives a really clear picture of the Dolce & Gabanna pricing strategy;
in July 2011, the majority of stock items at Dolce & Gabbana 
were discounted to 60% of MSRP for a few weeks followed by a further reduction to 50% MSRP.  Prices
returned to normal with no discounting at all until the first week of December, when again most stock items were
reduced to 60% of MSRP, this time for several months.  At the same time a small number of items were
reduced to 55% and 50% MRSP.  Finally in February most stock was reduced to 50% MSRP.  It is also
evident that the total number of stock items available has been severely reduced during February.

The point here isn't to demonstrate that Dolce & Gabbana 
respect the mantra of inventory turnover.  (They do!)
My point is that long-term monitoring and analysis of merchant
behavior can tell us a lot about the dynamics of a market segment
and help us understand the strategies of the major merchants.
