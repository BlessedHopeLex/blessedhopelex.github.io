---
sermon-title: Church History 1
google-drive-id: 1Y5K6C4SXv2ub4b8DwqhTG-Tqah3-adOU
start-time-seconds: 0
day-part: Evening
tags: wednesday-evening church-history
preacher: Zack Warren
layout: default
---

# {{ page.sermon-title }}

##### {{ page.date | date: "%A, %B %-d, %Y" }} {{ page.day-part }} Service

{% if page.start-time-seconds >= 1 %}
{% capture starts-at-time %}
{{ page.start-time-seconds | divided_by: 60 }}:{{ page.start-time-seconds | modulo: 60 }}
{% endcapture %}

{% include sermon-starts-at.md starts-at=starts-at-time %}
{% endif %}

{% capture video-id %}
{{ page.google-drive-id }}
{% endcapture %}

{% capture start-time %}
{{ page.start-time-seconds }}
{% endcapture %}

{% include google-drive-audio.md drive-id=video-id start-time=start-time %}

{::options parse_block_html="true" /}
<iframe src="https://onedrive.live.com/embed?cid=19DF4E5D38A1B8EB&resid=19DF4E5D38A1B8EB%2146795&authkey=AIyXAKJlENHfA4w&em=2" width="402" height="327" frameborder="0" scrolling="no"></iframe>
{::options parse_block_html="false" /}
