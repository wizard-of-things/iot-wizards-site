---
title: Intro
nav: true

---
# Environmental Dashboard

This includes 3 parts

* Esp8266 connected to a bme280 via i2c
* Esp8266 connected to a 2.8 inch nextion 2.8 inch display
* Raspberry Pi 3 , running docker container ,

{% include alert.md text="**Overall Setup**" color="primary" %}

{% capture overall 1 %}
Block diagram.
{% endcapture %}
{% include card.md text=plugs title="Block diagram" img="overall_block2.jpg" alt="overall_block2" %}

{% capture overall 2 %}
Shows docker container
{% endcapture %}
{% include card.md text=plugs title="Docker container" img="overall_block1.jpg" alt="overall_block1" %}