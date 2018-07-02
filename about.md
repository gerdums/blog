---
title: About this blog
layout: page
description: An optional about page for BlogInn Jekyll theme
banner_image: aboutPage.jpg
---

    <nav id="top" class="site-navigation">
        <div class="inner">
            <button id="menu-toggle" aria-expanded="false">Menu</button>
            <div class="nav-menu">
                <ul class="menu">
                {% for link in site.navigation %}
                  {% assign current = nil %}
                  {% if page.url == link.url %}
                    {% assign current = 'nav-current' %}
                  {% endif %}
                  <li class="{{ current }}">
                    <a class="{{ current }}" href="{{ link.url }}">{{ link.text }}</a>
                  </li>
                {% endfor %}
                </ul>        
            </div><!-- .nav-menu -->
            <a class="subscribe-button fa-feed square fill-horizontal" href="{{site.baseurl}}/feed.xml"><span class="screen-reader-text">Subscribe</span></a>
        </div><!-- .inner -->
    </nav><!-- .site-navigation -->

**John Doe** is a Senior Art Director from [Vilnius](https://en.wikipedia.org/wiki/Vilnius), Lithuania. After graduating from The College of Visual Arts with a degree in Communication Design, he worked for three small graphic design shops where he honed his design style and sensibility.

His work has been recognized by Communication Arts, Print, How, ID, IdN, AIGA, Effie, Archive, Graphis, AdFed and Rockport. Graphic Design USA named him a person to watch in 2015.

>The world always seems brighter when you’ve just made something that wasn’t there before. <cite>Neil Gaiman</cite>

As a hobby, John Doe authors the most influential design blog in Lithuania with over 100,000 page views a month. He lives in Vilnius with his beautiful wife, two boys and one girl.

*Thank You for reading!*
