---
layout: default
parent:  Towny
title: Residente de ciudad
permalink: /towny_residente
last_modified_date:   2023-05-20 16:27:53 -0600
nav_order: 2
---
<details open markdown="block">
  <summary>
	Contenido de página
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

# Siendo residente de una ciudad
Si no quieres toda la molestia de mantener en pie una ciudad, administrar regiones, modificar permisos, preocuparte por items robados, grifeos, y todo lo que implica ser líder de una ciudad, mejor solo únete a la ciudad de alguien más y disfruta de la vida de residente 😎

Aquí te explicaremos algunas cosas que tienes que tomar en cuenta si decides jugar como residente de una ciudad.

---
## Unirse a una ciudad
Para unirte a una ciudad hay 2 opciones, que [te inviten a una ciudad](#fui-invitado-a-una-ciudad), o [buscar una ciudad abierta](#quiero-unirme-a-una-ciudad-abierta), primero abordaremos el tema de invitación:

### Fui invitado a una ciudad
Si conoces a alguien con una ciudad, o alguien se apiada de tu cabecita de usuario nuevo, puede que te inviten a su ciudad, cuando esto pase mira tu chat, te tiene que haber llegado un mensaje que diga algo similar a "Has sido invitad@ a unirte a LaGranCiudadDeTuAmigo", para aceptar la invitación simplemente usa el comando que se te muestra en el chat (`/aceptar LaGranCiudadDeTuAmigo`), puedes escribirlo en el chat, o hacer click sobre el comando que te aparece ahí mismo, una vez que lo hagas te habrás unido a la ciudad de tu nuevo líder.

<details markdown="block">
  <summary>
	<strong>Comando(s) y ejemplo(s)</strong>
  </summary>
  
{: .comando}
> - `/aceptar nombreDeLaCiudad` - Acepta la invitación para unirte a la ciudad de la que ponga el nombre.

{: .ejemplo}
> - `/aceptar LaGranCiudadDeTuAmigo` - Aceptarás la invitación para unirte a la ciudad llamada "LaGranCiudadDeTuAmigo"
</details>

### Quiero unirme a una ciudad abierta
Una ciudad abierta es una ciudad a la que cualquier persona puede unirse sin necesidad de tener una invitación.

Para ver la lista de ciudades abiertas del servidor, usa el comando `/t list by open` y busca la ciudad que más te guste (TIP: Usa `/t nombreDeCiudad` para ver información sobre una ciudad).

Una vez que hayas encontrado tu ciudad ideal, usa el comando `/t join nombreDeciudad` para unirte a la ciudad... ¡y listo! ahora eres residente de una ciudad 🙂

<details markdown="block">
  <summary>
	<strong>Comando(s) y ejemplo(s)</strong>
  </summary>
  
{: .comando}
> - `/t list by open` - Para ver la lista de ciudades abiertas
> - `/t nombreDeCiudad` - Para ver información sobre una ciudad específica
> - `/t join nombreDeCiudad` - Para unirte a la ciudad que quieras (solo si esa ciudad es abierta)

{: .ejemplos}
> - `/t list by open` - Literalmente así se usa el comando, no hay mejor ejemplo xd
> - `/t EverLasting` - Te mostrará información sobre la ciudad *EverLasting*
> - `/t join EverLasting` - Te unirá a la ciudad *EverLasting* (si es que está abierta cuando uses el comando)
</details>
---

## Impuestos y otros costos de ciudad
¡Los impuestos son lo mejor!... dijo nadie, nunca... pero en Minecraft son necesarios para que los líderes de ciudad mantengan el lugar donde vives, aquí te diremos algunas cosas que deberías considerar sobre los pagos a tu ciudad...

### Costos generales
Para saber cuánto debes pagar de cualquier costo de ciudad, usa el comando `/towny prices`, esto te mostrará la información desglozada sobre todos los costos que podrías tener relacionados a tu ciudad y nación.

<details markdown="block">
  <summary>
	<strong>Comando(s) y ejemplo(s)</strong>
  </summary>
  
{: .comando}
> - `/towny prices` - Para ver costos de todo

{: .ejemplos}
> - `/towny prices` - Literalmente así se usa el comando, a que es sencillo ;)
</details>

### Impuestos
Para saber cuánto debes pagar de impuestos diarios (cada 24h, ajustado a tiempo del servidor), usa el mismo comando mencionado en [Costos generales](#costos-generales) (`/towny prices`) y busca la sección **Town**, luego busca la sección **Impuestos** y enfócate en la parte que dice "Residente: X.X%" (o algo similar), si hay un signo de porcentaje `%`, significa que el impuesto diario que se te cobra va en función de tu dinero actual, entre más dinero tengas, más impuestos se te cobran, si no tiene el símbolo de porcentaje, entonces pagarás un impuesto fijo y todos los residentes pagarán lo mismo.

Los impuestos se cobran cada 24 horas (de tiempo real) y puedes saber cuándo empezará el nuevo día (nuevo cobro) con el comando `/towny time`
<details markdown="block">
  <summary>
	<strong>Comando(s) y ejemplo(s)</strong>
  </summary>

{: .comandos}
> - `/towny prices` - Para ver costos de todo
> - `/towny time` - Para saber cuánto falta para el próximo día

{: .ejemplo}
> ### Situación #1
> {:.no_toc}
> Usas `/towny prices` y encuentras que la sección de impuestos de Residente dice **`10.0%`** y tu tienes `$1000` en tu cuenta...
> 
> Usas el comando `/towny time` y ves que faltan 10 minutos para el nuevo día (que conlleva un nuevo cobro), así que toca esperar por él...
>
> Una vez pasado el tiempo necesario, llega un nuevo día y se te cobra tu impuesto diario de ciudad, ya que tu ciudad cobra 10% sobre tu dinero, habrás pagado **$100.0 de impuestos**.
> ### Situación #2
> {:.no_toc}
> Usas `/towny prices` y encuentras que la sección de impuestos de Residente dice **`$10.0`** y tu tienes `$1000` en tu cuenta...
> 
> Usas el comando `/towny time` y ves que faltan 10 minutos para el nuevo día (que conlleva un nuevo cobro), así que toca esperar por él...
>
> Una vez pasado el tiempo necesario, llega un nuevo día y se te cobra tu impuesto diario de ciudad, ya que tu ciudad cobra un impuesto fijo de $10.0 y no un porcentaje, habrás pagado solo **$10.0 de impuestos**.
</details>