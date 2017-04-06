# Blog

This blog is built with [Jekyll](https://jekyllrb.com/).

The theme builds off
[Type Theme](https://rohanchandra.github.io/project/type/), and is
heavily inspired by [Otoro](http://blog.otoro.net/), the [New York
Times](http://www.nytimes.com/), and the
[Rosenrot](http://the-rosenrot.com/). The annals-like frontpage takes
cue from Paul Graham's [essays](http://paulgraham.com/articles.html)
and Cosma Shalizi's [notebooks](http://bactra.org/notebooks/).

I have more or less borrowed the theme wholesale from [Dustin Tran](https://dustintran.com)

The following Jekyll plugins are used:

+ [KaTeX](https://khan.github.io/KaTeX/), Google Fonts, Google Analytics, Normalize, Pygments (comes with TypeTheme)
+ [Jekyll Scholar](https://github.com/inukshuk/jekyll-scholar)

## Notes

There is a hack for in-text citations.
It copies apa, where the only difference is on lines 588-594. The file
is in `etc/`.
Also see [here](https://github.com/inukshuk/jekyll-scholar/issues/33).
```
  <layout suffix=")" delimiter="; ">
    <group delimiter=" ">
      <text macro="author-short"/>
      <text prefix="(" macro="issued-year"/>
      <text macro="citation-locator"/>
    </group>
  </layout>
```
