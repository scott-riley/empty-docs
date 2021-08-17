# A new page

{% embed url="https://loom.com/team-videos" %}

{% embed url="https://loom.com/blog" %}

{% swagger method="get" path="/hugh" baseUrl="https://app.com/api" summary="Get a Hugh" %}
{% swagger-description %}
Use this method to get information about a Hugh
{% endswagger-description %}

{% swagger-parameter in="path" name="id" type="Int" %}
The type of Hugh you want
{% endswagger-parameter %}

{% swagger-response status="200: OK" description="A valid Hugh!" %}

{% endswagger-response %}
{% endswagger %}
