News Feels (in News Feeds)
=======================

A still-hypothetical project to build a pipeline for aggregating political memes from Facebook.

# Background Reading
* [Inside Facebook’s (Totally Insane, Unintentionally Gigantic, Hyperpartisan) Political-Media Machine](http://www.nytimes.com/2016/08/28/magazine/inside-facebooks-totally-insane-unintentionally-gigantic-hyperpartisan-political-media-machine.html)

# How it'd work
`¯\_(ツ)_/¯`

## Computation
* Text acquisition: Luckily these things appear to be fairly OCR-able
* Face (ID) classification: Spot the face, tag the face. I _think_ there's good coverage for politicians in many face training DBS. If so we'll have to aggregate.

# Goals
1. Its an infrastructure: let this run as a service that's easy to set up and use as part of another project
2. Its really-well documented: Do you ust want "All The Facebook Memes" on your computer? Great - thats straightforward. Do you want to use this for an in-depth image and content analysis pipeline? Also incredibly straightfoward.
3. Can run as a hosted service for others
4. Doesn't violate anyone's ToS / IP rights
