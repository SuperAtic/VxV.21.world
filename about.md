---
title: La Filosofía VxV
layout: page
description: Filosofía
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

> El podcasting ha puesto patas arriba la economía de la radio, basada en la escasez.
> <cite>[Adam Curry](https://youtu.be/8RNsFNyCHL4?t=19964)</cite>

---

[![Adam hablando VxV @ BitBlockBoom 2022](/images/bitblockboom.jpg)](https://youtu.be/8RNsFNyCHL4?t=19964)

Mira la charla: [Adam Curry @ BitBlockBoom 2022](https://youtu.be/8RNsFNyCHL4?t=19964)

Escucha Adam hablando de VxV en [TFTC RIP #409](https://tftc.io/tftc-podcast/409-discussing-value-4-value-with-the-podfather-adam-curry/):
[![Adam talking VxV on TFTC](/images/409-Adam-Curry.png)](https://youtu.be/meAO2plwnXw)

---

El modelo VxV ofrece una solución al problema de la venta de información. A
solución que permite alejarse de la economía de la atención y la vigilancia
hacia una economía de _valor_, apertura y abundancia.

> La solución empieza por la aceptación. Selling digital content in the
> tradicional, transaccional, no funciona, o al menos no funciona muy
> bien. Una transacción de una fotografía digital de una manzana es muy diferente de una transacción de una manzana física.
>
> <cite>[Gigi D.][busking]</cite>

[busking]: https://dergigi.com/2021/12/30/the-freedom-of-value/#accept-the-nature-of-information

¿Quieres empezar? ¡Sigue una de las [guías]({{ '/guías' | absolute_url }})!