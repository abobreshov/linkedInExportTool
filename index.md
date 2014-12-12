---
layout: page
---
####Easily export Linkedin connections to XML or CSV file

The extension give you ability to export connections in Linkedin to Excel readable XML or CSV file.

* Easy to use and without any ads
* Export more than 1K connection per day
* Save your time upto 10 hours per week
* Can export contacts of particular contact

Looking for leads? Maybe need to find a right candidate? The tool can be very useful for you. Exported to excel contacts can be easily imported to CRM. 
Has a lots of contacts to export?

Exported Fields: __Full Name__, __Email__, __Phone__, __Location__, __Title__, __Industry__, __Company__, __Company Url__, __Distance__, __IM__, __Website__, __Profile Url__


<ul class="post-list">
{% for post in site.categories.news %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>