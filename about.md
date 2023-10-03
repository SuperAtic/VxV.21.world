---
title: The V4V Philosophy
layout: page
description: About
bodyClass: page-about
---

Value4Value es más de lo que parece. Es un modelo de monetización, un contenido
y un modo de vida. Se trata de libertad y apertura, conexión y libertad de expresión, dinero sano y resistencia a la censura.
libertad de expresión, el dinero sólido y la resistencia a la censura.

{% assign limit = 3 %}
{% assign piezas_clasificadas = sitio.piezas | clasificar: 'peso' %}
{% for pieza in piezas_clasificadas limit: limit %}
  - **{{ piece.title }}:** {{ piece.content | markdownify | strip_html | truncatewords: 33 }} [[more]]({{ piece.url | relative_url }})
{% endfor %}

Hay [múltiples piezas][pieces] que hacen que todo funcione, no menos importante de
que es bitcoin y su red relámpago que permite la fricción sin
automatización de micropagos. Una de las cosas más importantes que hay que entender es
que la información _no_ es escasa y por lo tanto tiene que ser monetizada y pensada
de otra manera. Se trata de un cambio mental crucial que es bastante difícil de hacer al principio.
pasar de una mentalidad de escasez a una mentalidad de abundancia.



[pieces]: {{ '/piezas' | absolute_url }}

> Podcasting really flipped the scarcity-based economy of radio broadcasting on
> its head.
>
> <cite>[Adam Curry](https://youtu.be/8RNsFNyCHL4?t=19964)</cite>

---

[![Adam talking V4V @ BitBlockBoom 2022](/images/bitblockboom.jpg)](https://youtu.be/8RNsFNyCHL4?t=19964)

Watch the talk: [Adam Curry @ BitBlockBoom 2022](https://youtu.be/8RNsFNyCHL4?t=19964)

Listen to Adam talk V4V on [TFTC RIP #409](https://tftc.io/tftc-podcast/409-discussing-value-4-value-with-the-podfather-adam-curry/):
[![Adam talking V4V on TFTC](/images/409-Adam-Curry.png)](https://youtu.be/meAO2plwnXw)

---

The V4V model provides a solution to the problem of selling information. A
solution that allows you to step away from the attention and surveillance
economy, towards an economy of _value_, openness, and abundance.

> The solution begins with acceptance. Selling digital content in the
> traditional, transactional way doesn't work, or at least doesn't work very
> well. A transaction involving a digital photograph of an apple is very
> different than a transaction involving a physical apple.
>
> <cite>[Gigi D.][busking]</cite>

[busking]: https://dergigi.com/2021/12/30/the-freedom-of-value/#accept-the-nature-of-information

Want to get started? Follow one of the [guides]({{ '/guides' | absolute_url }})!