# Smithsonian Data Fun

I futzed with the code that Matt Miller developed, and all I got was this dumb word cloud.

What I did was:
- run [Matt's code](https://github.com/thisismattmiller/smithsonian-open-access) to parse the 11M Smithsonian open metadata records
- extracted all the names found in all the records using [pandas](https://pandas.pydata.org/) (but [jq](https://stedolan.github.io/jq/) is also super fun and useful to use with the output of Matt's scripts)
- then I used Matt's [fanart drawing of the right tower of the Smithsonian Castle](https://thisismattmiller.com/img/post_si_castle.png) as an image mask for a word cloud
- then I made a static IIIF representation of that image
- then I added it to Github and then I tweeted about it, and that's how we got here.

But seriously, here are some fun links of Matt's work and others that I was able to sew together in a few hours to fun effect:

- [The Smithsonian Open Access release that started it all](https://www.si.edu/openaccess)
- [Matt's Tweet about his data analysis and data viz efforts that started it all more specifically](https://twitter.com/thisismmiller/status/1233406325943668738) 
- [Matt's blog post about his process and viz examples, also including fun easter eggs at the bottom which is where I got the fanart image of the Smithsonian Castle](https://thisismattmiller.com/post/smithsonian-open-access-data-release/)
- [The Python wordcloud library I used](https://github.com/amueller/word_cloud)
- [The static IIIF tile generator I used](https://github.com/zimeon/iiif/tree/master/demo-static)
- [My wordcloud as IIIF](https://hadro.github.io/smithsonian_data/)
