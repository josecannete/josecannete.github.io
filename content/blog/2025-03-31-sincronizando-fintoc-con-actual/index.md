---
title: Sincronizando Fintoc con Actual Budget para automatizar mis finanzas personales
date: 2025-03-31
summary: Sincronizando Fintoc con Actual Budget para automatizar mis finanzas personales
---

Llevo un buen tiempo usando [Actual Budget](https://actualbudget.org/), un tremendo software open source para llevar el control de mis finanzas personales. Me ha servido muchísimo para entender en qué se me va la plata y manejar mejor mis gastos.

Llevar el registro manual de mis gastos ha sido un buen ejercicio, pero ya era hora de automatizarlo un poco. Así que decidí intentarlo.

El fin de semana me dediqué a conectar Fintoc con Actual Budget. Fintoc me permite traerme mis transacciones bancarias de forma súper fácil, y Actual, al ser open source, tiene una API con la que se puede trabajar sin problema. Sonaba bacán en teoría, pero había un detalle: aunque soy programador, casi nunca he trabajado fuera de Python, y en este caso, la API de Actual estaba en Node.js (y Fintoc también tenía una disponible para Node). Así que tocó aprender sobre la marcha y darle nomás.

Como no cachaba mucho ni de Node, ni de Javascript, me apoyé bastante en GitHub Copilot (sobre todo en Claude 3.7 Sonnet Thinking). Fue una ayuda tremenda: le pedí soluciones para errores que me aparecían, que me refactorizara código y hasta ayuda para implementar nuevas funcionalidades. De a poco fui agarrándole la mano a Node y JavaScript.

Todavía hay varias cosas que quiero mejorar, como agregar categorías de gastos desde el principio, automatizar su asignación según la descripción de las transacciones y manejar bien los payees. Pero quedé súper contento con lo que logré en tan poco tiempo. Me gustó mucho cómo la IA me ayudó a codear, así que voy a seguir experimentando.

Si quieren probarlo, acá les dejo el repo donde seguiré trabajando: [https://github.com/josecannete/actual-fintoc](https://github.com/josecannete/actual-fintoc)

Si tienen sugerencias o tips de cómo están usando estas herramientas ustedes, cuentenme porfa!