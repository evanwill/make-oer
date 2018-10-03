<div class="card mb-3">
{% if include.img %}<img class="card-img-top" src="{{ include.img | prepend: '/images/' | absolute_url }}" alt="Card image cap">{% endif %}
{% if include.header %}<h5 class="card-header">{{ include.header }}</h5>{% endif %}
<div class="card-body">
{% if include.title %}<h5 class="card-title">{{ include.title }}</h5>{% endif %}
<div class="card-text" markdown="1">

{{ include.text }}

</div>
</div>
</div>