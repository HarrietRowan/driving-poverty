---
layout: static
title: 
permalink: /contact/
---

<section id="contact" class="container content-section text-center col-md-offset-0">
    <div class="row">
        <div class="col-md-8 col-md-offset-0">
            <p><a href="mailto:{{ site.email }}">{{ site.email }}</a>
            </p>
            <ul class="list-inline banner-social-buttons">
                {% for network in site.social %}
                <li>
                    <a href="{{ network.url }}" class="btn btn-default btn-lg"><i class="fa fa-{{ network.title }} fa-fw"></i> <span class="network-name">{{ network.title }}</span></a>
                </li>
                {% endfor %}
            </ul>
        </div>
    </div>
</section>