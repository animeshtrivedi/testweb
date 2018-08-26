---
layout: default
---
{% raw %}
<a href="/images/animeshtrivedi-large.jpeg" title="View larger picture"><img src="/images/animeshtrivedi-small.jpeg" alt="Photo of Animesh Trivedi"
style="float:right;width:25%;max-width:150px;margin-left:15px;"/></a>
{% endraw %}

I am Research Staff Member (RSM) in Cloud and Computing Infrastructure group at the IBM Research Lab, Zurich Switzerland. 

My main research areas are networking, operating systems, and distributed systems. Broadly speaking, I am interested in the performance aspect of systems, spanning from multi-core CPUs to distributed environments. Currently, I am investigating how modern high-performance devices (100+ Gbps network, NVMe/3DXP storage, etc.) can be leveraged in large-scale data-processing systems such as Spark, Tensorflow, serverless workloads. I am one of the founding contributors of the [Apache Crail (Incubating)](https://crail.incubator.apache.org/) project. 


### What is new
<ul class="news list-unstyled">
{% for post in site.tags.whatsnew limit: site.front_page_news %}
    {% if post.shortnews %}
        <li class="shortnews">
            <span class="date">{{ post.date | date: "%B %-d, %Y" }}</span>
            {{ post.content }}
        </li>
    {% else %}
        <li class="bloglink">
            <span class="date">{{ post.date | date: "%B %-d, %Y" }}</span>
            <a href="{{ post.url }}">&raquo; {{ post.title }}</a>
        </li>
    {% endif %}
{% endfor %}
</ul>
{% assign numposts = site.categories.news | size %}
{% if numposts >= site.front_page_news %}
<p><a href="{{ site.base }}/news/">more posts&hellip;</a></p>
{% endif %}


### Contact
Email me at: firstname.lastname@alumni.ethz.ch. I am also on [Github](https://github.com/animeshtrivedi) and [LinkedIn](https://ch.linkedin.com/in/animesh-trivedi-5407aa2).

### Selected Recent Publications

  * Pocket: Ephemeral Storage for Serverless Analytics. Ana Klimovic, Yawen Wang, and Christos Kozyrakis, Patrick Stuedi, Animesh Trivedi, and Jonas Pfefferle, in the 13th USENIX Symposium on Operating Systems Design and Implementation (OSDI'18), Carlsbad, CA, 2018. 

  * Albis: High-Performance File Format for Big Data Systems. Animesh Trivedi, Patrick Stuedi, Jonas Pfefferle, Adrian Schuepbach, and Bernard Metzler, in the 2018 USENIX Annual Technical Conference (ATC), Boston, MA, USA, July 11-13, 2018.

  * Navigating Storage for Serverless Analytics. Ana Klimovic, Yawen Wang, Christos Kozyrakis, Patrick Stuedi, Jonas Pfefferle, and Animesh Trivedi, in the 2018 USENIX Annual Technical Conference (ATC), Boston, MA, USA, July 11-13, 2018.

Full list is <a href="{{ site.base }}/publications/"> here</a>.


### Program Committees
  * ACM SYSTOR (2019)
  * ACM/IEEE CCGrid (2019) 

