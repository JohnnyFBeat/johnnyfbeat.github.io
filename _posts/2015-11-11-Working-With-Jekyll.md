---
layout: post
title: Working With Jekyll
categories: journal
tags:
  - documentation
  - sample
image:
  feature: bag.jpg
  teaser: bag-teaser.jpg
  credit: null
  creditlink: null
published: true
---


### Posts

You will find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works. If you already have a website built with Jekyll, simply copy over your posts.

<div id="map" style="height: 400px;"></div>
<script>
var map = L.map('map').setView([51.4833, -3.1833], 10);

L.tileLayer('https://api.mapbox.com/styles/v1/mapbox/light-v9/tiles/256/{z}/{x}/{y}?access_token=pk.eyJ1Ijoiam9obm55ZmJlYXQiLCJhIjoiY2oxbzF6emc2MDAzMzJxbW5pMmsycW10aSJ9.Daey0MGA6uFQ5XWAW7BV0w', {
    attribution: 'Map data &copy; <a href="http://openstreetmap.org">OpenStreetMap</a> contributors, <a href="http://creativecommons.org/licenses/by-sa/2.0/">CC-BY-SA</a>, Imagery © <a href="http://mapbox.com">Mapbox</a>',
    maxZoom: 18,
    id: 'your.mapbox.project.id',
    accessToken: 'your.mapbox.public.access.token'
}).addTo(mymap);
</script>



### Configuration

To change site settings, edit the `_config.yml` file found in the root of your repository. Anything under 'Site Settings' can be tweaked to your liking.

If you are hosting your site on GitHub Pages, then committing a change to the `_config.yml` file will force a rebuild of your site with Jekyll. Any changes made should be viewable soon after. If you are hosting your site locally, then you must run `jekyll serve` again for the changes to take place.

In the `_config.yml` file, you'll be able to change the title of your site along with any tagline you want, which shows up in the site header, as well as the description of your site for SEO purposes. You can also change the social media information, and add your own social media icons.

### Everything Else

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
