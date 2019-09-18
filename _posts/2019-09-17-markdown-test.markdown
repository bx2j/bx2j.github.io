---
title: "Markdown test"
layout: post
image: /assets/images/*.jpg
headerImage: false
tag:
- markdown
- test
category: blog
author: bx2j
description: Markdown test
---

### test1 - link
- [test2](#test2)

### test2 - highlight
<span class="evidence">Paragraphs can be written like so. A paragraph is the basic block of Markdown. A paragraph is what text will turn into when there is no reason it should become anything else.</span>

{% highlight html %}
<span class="evidence">Paragraphs can be written like so. A paragraph is the basic block of Markdown. A paragraph is what text will turn into when there is no reason it should become anything else.</span>
{% endhighlight %}

### test3
** bold **
**Image** on the left and **Text** on the right:

{% highlight html %}
<div class="side-by-side">
    <div class="toleft">
        <img class="image" src="{{ site.url }}/{{ site.picture }}" alt="Alt Text">
        <figcaption class="caption">Photo by bx2j</figcaption>
    </div>

    <div class="toright">
        <p>bx2j</p>
    </div>
</div>
{% endhighlight %}

<div class="side-by-side">
    <div class="toleft">
        <img class="image" src="{{ site.url }}/{{ site.picture }}" alt="Alt Text">
        <figcaption class="caption">Photo by bx2j</figcaption>
    </div>

    <div class="toright">
        <p>bx2j</p>
    </div>
</div>

**Text** on the left and **Image** on the right:

{% highlight html %}
<div class="side-by-side">
    <div class="toleft">
        <p>bx2j</p>
    </div>

    <div class="toright">
        <img class="image" src="{{ site.url }}/{{ site.picture }}" alt="Alt Text">
        <figcaption class="caption">Photo by bx2j</figcaption>
    </div>
</div>
{% endhighlight %}

<div class="side-by-side">
    <div class="toright">
        <img class="image" src="{{ site.url }}/{{ site.picture }}" alt="Alt Text">
        <figcaption class="caption">Photo by bx2j</figcaption>
    </div>

    <div class="toleft">
        <p>bx2j</p>
    </div>
</div>