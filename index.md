---
layout: page
---
####Easily export Linkedin 1st connections to XML or CSV file

This extension enables you to export first connections in Linkedin to Excel readable XML or CSV file.
If you a recruter it can be very useful for finding candidates.
Also it could be helpful for leads finding. 

Features:
* Easy to use, free and without any ads
* Export more than 1K connection per day
* Save your time upto 10 hours per week

Exported Fields: Full Name, Email, Phone, Location, Title, Industry, Company, Company Url, Distance, IM, Twitter, Profile Url

How to Use <!-- make it as reference -->

For bug reports or additional information, please write to li.exporttool@gmail.com


<ul class="post-list">
{% for post in site.categories.news %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>