---
gallery_nav:
  - title: Inflated Bars
    url: "#inflated-bars"
  - title: Left Leaning
    url: "#left-leaning"
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

<!-- https://www.reddit.com/r/dataisugly/comments/1fquipe/so_confusing/ -->
