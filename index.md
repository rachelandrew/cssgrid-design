---
layout: home
title: CSS Grid in Production
---

# These sites are using CSS Grid

{% assign gridsites = site.gridsites %}
<ul class="post-list">
           {% for gridsite in gridsites %}
           <li>
             <h2><a href="{{gridsite.gridsite-url}}">{{gridsite.gridsite-name}}</a></h2>
             <div class="details">


                   {{gridsite.content}}

                   <p>Site by <a href="{{ gridsite.gridsite-author-url }}">{{ gridsite.gridsite-author }}</a>.{% if gridsite.gridsite-writeup %} <a href="{{ gridsite.gridsite-writeup }}">Read the writeup</a> {% endif %}</p>
             </div>

           </li>
           {% endfor %}
         </ul>

_To add a site [submit a pull request](https://github.com/rachelandrew/cssgrid-design) adding the site as a new file in the `_gridsites` folder. [Find out more](/about)_

