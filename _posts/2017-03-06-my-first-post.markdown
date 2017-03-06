---
layout: post
title:  "My first post"
date:   2015-02-12 13:46:40
categories: jekyll update
---
Because of Jekyll’s flexibility, there are many solutions to how to do this. One common solution is to create a folder in the root of the project directory called something like assets or downloads, into which any images, downloads or other resources are placed. Then, from within any post, they can be linked to using the site’s root as the path for the asset to include. Again, this will depend on the way your site’s (sub)domain and path are configured, but here are some examples (in Markdown) of how you could do this using the site.url variable in a post.

Including an image asset in a post:
{% highlight ruby %}
... which is shown in the screenshot below:
![My helpful screenshot]({{ site.url }}/assets/screenshot.jpg)
{% endhighlight %}

Linking to a PDF for readers to download:

{% highlight ruby %}
... you can [get the PDF]({{ site.url }}/assets/mydoc.pdf) directly.
{% endhighlight %}

