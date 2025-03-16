---
gallery_nav:
  - title: Inflated Bars
    url: "#inflated-bars"
  - title: Left Leaning
    url: "#left-leaning"
  - title: A Plot of Bubblies
    url: "#a-plot-of-bubblies"
  - title: Lines Outside the Drawing
    url: "#lines-outside-the-drawing"
  - title: Mental Health Soup
    url: "#mental-health-soup"
  - title: Wage Imbalance
    url: "#wage-imbalance"
  - title: Giants and Pixies
    url: "#giants-and-pixies"
  - title: The Death of Music
    url: "#the-death-of-music"
  - title: Heat Share
    url: "#heat-share"
---

# VisLies 2024 Gallery

This year, hurricanes Helene and Milton wreaked havoc on Florida where the [IEEE
Vis conference] and hence [VisLies] was supposed to be. So, this year back to
meeting online.

[IEEE Vis conference]: https://ieeevis.org/year/2024/welcome
[VisLies]: https://www.vislies.org/


## Inflated Bars

{{< image src="inflated-bar-chart.jpg"
          align="right"
          width="300px"
          lie="top-right" >}}

[Ken Moreland] started us off with this quick example. Here we see what appears
to be a bar chart, but it makes not sense. First of all, the bars do not
adequately reflect the values of the poll. Perhaps this was never intended to be
a bar chart, but it's layout is confusing.

But even worse, inflation seems to be affecting these numbers. More than 100% of
people said no, and even more said yes. We suspect someone made a math error.

[Ken Moreland]: https://www.kennethmoreland.com/

<!-- https://www.reddit.com/r/funny/comments/uxigrx/a_very_helpful_graph/ -->

## Left Leaning

{{< image src="young-lean-left-mobile.png"
          align="right"
          width="200px"
          lie="top-right" >}}

<!-- https://www.reddit.com/r/dataisugly/comments/1fquipe/so_confusing/ -->

[Ken][Ken Moreland] presented this plot from [a recent Washington Post article].
The plot, according to its title, demonstrates how young women are more likely
to have liberal views than older women.

However, there are numerous things that make this plot confusing. First of all,
the labeling of men and women is quite confusing. The clearest way to label
would be to put each label directly over the corresponding plot. Instead, each
plot is labeled with a number, 1 or 2, with a legend underneath. To make it even
more confusing, the numbers are reversed: 2 then 1. All this makes it difficult
to keep them straight.

Additionally, the x-axis is confusing. The line at the bottom makes it look like
a continuous range. You have to notice that the numbers restart. This is made
even harder as the numbering is inconsistent between the two plots.

{{< image src="young-lean-left.png"
          align="left"
          width="400px"
          lie="top-right" >}}

These aforementioned problems do get fixed in the desktop version. However,
there are further problems. In particular, the y-axis in either case makes no
sense. Why is the maximum less than 1%? Since one of the three groups is
everyone not in the first two, the numbers should add up to 100%. Perhaps a
mistake was made where the numbers are fractions, and a `%` was added without
multiplying by 100.

But the real lie of the data is the inference that younger voters lean blue,
meaning either they have more progressive rather than conservative ideology or
they prefer the Democratic party. However, this is not well supported in the
data. In fact, for both men and women, the percentage registered as Democratic
is pretty even, which contradicts the statement of the title.

What the data does say is that young voters are less likely to be Republican
than older voters. It is a reasonable hypothesis that the reason is young voters
tend to be less conservative. But there could be other reasons. It could be that
these young voters are joining even more right-leaning parties. It could be that
plenty of young voters have conservative ideologies that don't match that of
most Republican candidates.

To be fair, the article this plot comes from has this statement: "Older folks
register Republican more often than their younger buddies with the very same
name, presumably because younger voters lean left." The plot does support this
statement (with the exception that names are not shown here). And the statement
also declares that the explanation of young voters leaning left is just a
presumption. However, the presentation of this supporting visualization leaves a
false impression that could easily spread.

[a recent Washington Post article]: https://www.washingtonpost.com/business/2024/09/13/popular-names-republican-democrat/


## A Plot of Bubblies

{{< image src="beer-thumbnail.jpg"
          link="beer.jpg"
          align="right" >}}

<!-- https://www.reddit.com/r/Infographics/comments/16eaw4n/globalper_capita_beer_consumption_in_2021 -->

[Ken][Ken Moreland] shared this [infographic on beer consumption]. There is a lot
to say about it.

The first thing to notice is its interesting representation of parts of a whole.
This representation is a [Voronoi Treemap]. It takes a circular space and
divides it into regions whose areas are proportional to the value they
represent. It is being used as a glorified pie chart. It looks fancy and
stylistically themed as the bubbles at the top of a glass of beer. This
representation seems more form over function, but let's put a pin in that and
get back to it later.

A bigger issue with the chosen form of the presentation is the presentation of
values as absolutes rather than per capita. This is correct for the chosen
representation, but it is antithetical to the point of the graphic. Knowing the
total amount of beer sold in each region might be useful to a beer distributor,
but it is useless to understand cultural differences. For example, Czechs drink
on average almost twice as much beer as any other nationality (as can be seen by
the much more useful bar chart at the bottom). But their representation in the
graphic is so small as to be hard to find.

It is also worth noticing the text on the top right:

> Every region in the world increased its overall beer consumption in 2021
> compared to 2020, with global consumption increasing by 4% (7.1 billion
> liters).

Unfortunately, nothing in this infographic supports this statement. All data is
given as a snapshot in 2021. The provided data tells you nothing about beer
consumption in 2020 or how it might have changed. (That doesn't make the
statement false. It is just unrelated to anything on the infographic.) Also, the
population tends to increase from year to year, which could account for any
increase in beer consumption. Did people drink more beer, or did more people
drink beer? It could be that more people drank less beer, which is counter to
this statement.

[infographic on beer consumption]: https://www.visualcapitalist.com/which-countries-drink-the-most-beer-2/
[Voronoi Treemap]: https://doi.org/10.1109/INFVIS.2005.1532128

Circling back to the [Voronoi Treemap], it is an interesting display. The method
was originally proposed in 2005. That was a while ago, and we have not seen much
use of them until recently. For some reason, in the last couple years we have
seen this representation a lot.

{{< image src="voronoi1.png" width="100%" >}}

I mean a _lot_.

{{< image src="voronoi2.png" width="100%" >}}

I mean like a really whole lot.

{{< image src="voronoi3.png" width="100%" >}}

<!--
Diamond: https://www.reddit.com/r/Infographics/comments/16wxeb4/the_10_largest_diamond_producing_countries_in_2022/
Spotify: https://www.reddit.com/r/Infographics/comments/16x9eut/oc_the_most_popular_spotify_artists/
Stock market: https://www.reddit.com/r/Infographics/comments/16u7zy1/the_109_trillion_global_stock_market_in_one_chart/
Oil: https://www.reddit.com/r/Infographics/comments/16ritj9/the_worlds_biggest_oil_producers/
Car: https://www.reddit.com/r/Infographics/comments/163n4qj/oc_the_25_biggest_automakers_in_the_world/
Global economy: https://www.reddit.com/r/Infographics/comments/15yzzor/estimate_global_gdp_distribution_in_2050/
Wine: https://www.reddit.com/r/Infographics/comments/15wcuqj/global_wine_producers_by_country/
World economy 2023: https://www.reddit.com/r/Infographics/comments/17kkcxd/world_economy/
World economy 2022: https://x.com/VisualCap/status/1546931869064630273
Billionaires: https://www.reddit.com/r/Infographics/comments/1cgbrj4/which_country_has_the_most_billionaires_in_2024/
Drug funds: https://www.reddit.com/r/Infographics/s/u8GsMDd2vq
Aircraft orders: https://www.reddit.com/r/Infographics/comments/1d0uv4f/largest_orders_of_aircraft/
Natural gas: https://www.reddit.com/r/Infographics/s/gAswfOT8KS
Amazon subsidies: https://www.reddit.com/r/Infographics/comments/1dngb0v/how_america_subsidizes_amazon/
U.S. Debt: https://www.reddit.com/r/Infographics/comments/1drecl5/foreign_holders_of_us_debt/
Causes of death: https://www.reddit.com/r/Infographics/comments/1e45tx8/oc_top_25_causes_of_death_worldwide/
World debt: https://econdaddy.com/macro/global-debt-in-one-infographic-ib-economics-tutor-commentary-macroeconomics-article-2019/
Plastic Waste: https://x.com/VisualCap/status/1627035863631937537
Global Distributions of Total Wealth: https://www.reddit.com/r/Infographics/s/b8IBdKtJGi
American's Portfolio: https://www.reddit.com/r/dataisugly/comments/1fydll3/why_cant_it_just_be_a_normal_pie_chart/
Top Coffee Producers: https://x.com/VisualCap/status/1670461796161912832
Semiconductor Foundries: https://x.com/VisualCap/status/1731916513907454009
Carbon Emissions: https://x.com/VisualCap/status/1722690819960733961
America vs. the World: https://x.com/VisualCap/status/1586583877476392962
Successfully Launched Rockets: https://www.reddit.com/r/Infographics/comments/1f7napp/successfully_launched_rockets/
A World of Languages: https://www.reddit.com/r/Infographics/comments/1f982gc/a_world_of_languages/
EU Economy: https://x.com/VisualCap/status/1669721901269147648
-->

Voronoi Treemaps seem to be a new trend. Are they good? There are not yet any
direct test on the efficacy of these displays, but there are reasons to believe
it is not the clearest display of information. Like pie charts, Voronoi Treemaps
have a clear parts-of-whole metaphor and can simultaneously show both items and
groups of items. They are also visually engaging. However, Voronoi Treemaps rely
on area to represent values, and this is [known to be perceptually nonlinear].
Furthermore, the technique makes highly irregular shapes, which might further
interfere with comparisons.

{{< image src="voronoi-shape-fit.jpg"
          width="400px"
          align="left" >}}

[Dave Pugmire] highlighted how these Voronoi plots may be more problematic than
pie charts. At first glance, it looks like the blue region takes up half of the
chart. However, it actually takes up 61% of the area. It takes a very close
inspection to see that whereas in a pair chart this would be obvious based on
the angles formed by the wedges. Likewise, the irregular shapes are difficult to
resolve. On the left of this image, [Dave][Dave Pugmire] has taken outlines of
some of the regions and overlaid them. Even when free to move the shapes around,
it is difficult to resolve how, for example, 3 of the 1% regions fit into the 3%
region.

[known to be perceptually nonlinear]: https://makingmaps.net/2007/08/28/perceptual-scaling-of-map-symbols/
[Dave Pugmire]: https://www.ornl.gov/staff-profile/dave-r-pugmire


## Lines Outside the Drawing

{{< image src="gaussian-outline.png"
          align="right"
          width="330px"
          lie="top-left" >}}

[Bernice Rogowitz] presented this [heat map]. Because this is VisLies, we can't
help but notice that the map is using a careless rainbow color map. There is a
perceptually salient change of colors around the value of 270, meaning that
value will stand out more noticeably than others. Is this value more
semantically important?

However, the real interesting part of this chart is the curve drawn on top of
the plot to mark the shape of a Gaussian distribution. Such annotations can be
helpful in pointing out the structure of data, but you have to be careful. It
can also inappropriately adjust the interpretation of the data. In this case,
the data appears to follow the Gaussian curve, but is there more to it?

{{< image src="gaussian-outline-plus.png"
          align="right"
          width="330px" >}}

On closer inspection, we see that the data does not follow the Gaussian curve
completely. The middle is more shallow than a Gaussian and there is a clear
feature at the right. Perhaps this more detailed curve is a more honest
representation of the distribution.

Even this curve does not catch all the features in the data. The data on the
left side of the plot has lower values than on the right. There is also a lower
group of values in the middle of the "Gaussian." All these features are easier
to miss when your attention is drawn to a single curve.

[Bernice Rogowitz]: https://sites.google.com/site/bernicerogowitz/
[heat map]: https://en.wikipedia.org/wiki/Heat_map


## Mental Health Soup

{{< image src="mental-health-soup.jpeg"
          align="right"
          width="400px" >}}

<!-- https://www.soundvision.com/article/raising-awareness-about-mental-health -->

[Bernice][Bernice Rogowitz] found this diagram on a web site about raising
awareness for mental health. The image seems to resemble a [mind map] concerning
the factors of mental health. However, the connections all seem to be one level
away from a single root, which does not impart any structure. There are colors,
but the colors seem to draw together unrelated items. For example, the purple
words, brain antidepressant, disorder, and help, have no real relationship with
each other. 

In the end, the the chart is just a haphazard mishmash of terms. Then again,
maybe that's the point.

[mind map]: https://en.wikipedia.org/wiki/Mind_map


## Wage Imbalance

{{< image src="price-vs-wages-bad-thumbnail.jpg"
          link="price-vs-wages-bad.jpg"
          align="right"
          width="300px"
          lie="top-left" >}}

[David Borland] presented this barely visualization infographic. The visual
elements are triangles that presumably mean increasing and colors that are green
for good and red/orange for bad. The important data is represented in two
numbers: an increase of 21% for grocery prices and an increase of 3.8% for
wages. Clearly, the increase of grocery prices far outweighs increases in wages.

But look more closely at the text below each triangle. Under the grocery prices
triangle, it states that the increase is for the period since January 2021,
which is a period of 3 years and 8 months (this graphic was presented October 1,
2024). However, under the wages triangle it states that the increase is for the
period since last September, which presumably means for the previous year. The
increase of two things over different periods of time makes them incomparable.
The fact that the grocery period is extended so much longer makes it even worse.

{{< image src="price-vs-wages.jpg"
          align="right"
          width="400px" >}}

Here is a more reasonable way to look at this data. Here we see the consumer
price index along with the average hourly earning of all employees. We can see
that there was a sharp increase in prices in 2022, but those increases have
leveled. Wages have been steadily increasing and were closing the gap. Thus, we
can see that in addition to making an unfair comparison with different time
scales, there is cherry picking happening. During the time of the previous year
that the infographic measured wage increases, prices had leveled off.

Although simple, this is a particularly egregious lie. Grocery prices were
reported as a [high contributing factor to the 2024 U.S. presidential election]
(which happened after [David's][David Borland] presentation but before this
writeup). Exaggerations of this nature can swing voters away from issues they
would otherwise prioritize as more important.

[David Borland]: https://davidborland.github.io/webpage/
[high contributing factor to the 2024 U.S. presidential election]: https://www.cnn.com/2024/11/14/economy/trump-grocery-prices-inflation/index.html

## Giants and Pixies

{{< image src="average-male-height.jpg"
          width="300px"
          align="right"
          lie="top-right" >}}

[David][David Borland] next presented this gem of a chart. It uses scaled
figures of people to demonstrate the average hight across a selection of
countries. That said, the relative sizes should be suspect. The pixie-sized
Indonesian comes only to the knee of the Netherlands' giant.

Of course, these sizes do not reflect the actual relative hight of people.
Rather, this is an artifact of the base of the chart not descending down to
zero. This highlights the importance of ensuring that the hight of bars (or
whatever objects you are using) are properly scaled from a 0 value. If they are
not, then the relative sizes are nonsense, which leads to a humorous effect
here.

<!-- Source: https://www.reddit.com/r/mildlyinfuriating/comments/zjxkf7/so_many_things_wrong_with_this/ -->


## The Death of Music

{{< image src="music-death-thumbnail.jpg"
          link="music-death.jpg"
          width="400px"
          align="right"
          lie="top-right" >}}

[Dave Pugmire] presented this deadly example of plotting. The plot shows the
average age of death for musicians of different genres. There are numerous
problems with this presentation.

First, the mode of plotting is wrong. The line chart implies there is some
progression of values such as change over time. However, there is not any real
progression from one music genre to the next. It would be more appropriate to
use a bar chart to convey that these are separate categories.

Second, why are the average US life expectancy lines changing? The average US
life expectancy is independent of musicians genres. It should be a flat
horizontal line. Are they somehow showing the life expectancy of music fans?
Is it changing according to some value like time that is not shown at all?

Third, it has been observed that some of the music genres are newer than others.
The blues genre is well over 100 years old, so plenty of blues musicians have
lived full natural lives. Old age deaths bring up the overall value. However,
rap and hip hop are much younger. Some of the earliest musicians in this genre
are still alive. The deaths counted for these genres only include those artists
who have died early, which dramatically reduces the overall value.


## Heat Share

{{< image src="temp-per-capita-thumbnail.jpg"
          link="temp-per-capita.jpg"
          width="400px"
          align="right"
          lie="top-right" >}}

[Dave][Dave Pugmire] also presented this interesting plot of world temperature.
However, it won't take long to notice some strange things about it. Some of the
coldest places on Earth such as Greenland and Antarctica are labeled as the
warmest whereas some countries with warm climates like India are labeled as
cold.

The reason is that this map is not showing temperature. Rather, it is showing
temperature per capita. That is, it is the temperature divided by the number of
people in the region. If this sounds like nonsense, that is because it is.

In fairness, this is probably an intentionally silly parody. But it does bring
up an interesting point about displaying values per capita. We've advocated at
VisLies! multiple times for [displaying map values as per capita]. However, this
only applies when displaying values affected by people such as number of votes,
number of buildings, number of accidents, number of infections, number of 5G
towers, etc. These type of values are usually heavily influenced by the number
of people in a region and often only give an indication of relative population.
This is fixed by providing the values per capita.

However, the temperature of a region is not (heavily) affected by the population
in that region, so showing temperature per capita is problematic for the same
reasons that showing, say, the consumption of peanut butter without it. We are
just seeing the inverse of population with low population (e.g., Greenland)
showing high and high population (e.g., India) showing low.

[displaying map values as per capita]: https://www.vislies.org/2021/gallery/#a-bigger-pool
