---
gallery_nav:
  - title: Inflated Bars
    url: "#inflated-bars"
  - title: Left Leaning
    url: "#left-leaning"
  - title: A Plot of Bubblies
    url: "#a-plot-of-bubblies"
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

[known to be perceptually nonlinear]: https://makingmaps.net/2007/08/28/perceptual-scaling-of-map-symbols/
