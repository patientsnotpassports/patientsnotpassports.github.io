---
layout: home
---

<div class="card-deck">
  {% include card.html title="Step by step advocacy guide" subtitle="For health workers"    href="/advocate/advocacy-guide-for-healthcare-workers" image="/img/healthcare-workers.jpg" %}
  {% include card.html title="Step by step advocacy guide" subtitle="For community workers" href="/advocate/advocacy-guide-for-community-workers" image="/img/community-workers.png" %}
</div>
<div class="card-deck">
  {% include card.html title="Learn"    subtitle="Learn about immigration checks and charging in the NHS" href="/learn"    image="/img/learn.jpg" %}
  {% include card.html title="Campaign" subtitle="Start a campaign in your local area"                    href="/campaign" image="/img/campaign.jpg" %}
</div>

<ul>
{% for page in site.pages %}
  <li><a href="{{ page.url }}">{{ page.title }}</a></li>
{% endfor %}
</ul>
