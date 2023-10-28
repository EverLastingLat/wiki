---
layout: default
parent:  Towny
title: Lider de ciudad
permalink: /towny_lider
last_modified_date:   2023-05-20 16:27:53 -0600
nav_order: 0
---
<details open markdown="block">
  <summary>
	Contenido de página
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

# Dirigiendo una ciudad

## Crea tu ciudad
El primer paso para tener la mejor ciudad es, obviamente, tener una ciudad, para esto puedes usar el comando `/t new nombreDeCiudad` para crear tu nueva ciudad, pero tienes que tomar en cuenta algunas cosas:

Crear una ciudad **tendrá un costo**, ¿cuánto costará? eso depende la nivelación de la economía actual, para ver el costo actual puedes usar el comando `/towny prices` y buscar el costo de una nueva ciudad (debería estar hasta arriba de los precios).

Antes de crear la ciudad tienes que **ubicarte en la zona donde quieres** que se encuentre el inicio de la ciudad, si quieres ver exactamente la ubicación, puedes presionar `F3+G` para ver las delimitaciones de chunks, que son las mismas limitaciones de cada plot de ciudad, cuando sepas dónde quieres hacer tu ciudad, párate en ese lugar y usa el comando de creación de ciudad.

Una vez creada la ciudad puedes [invitar a más gente](#invitar-a-nuevos-ciudadanos) o enfocarte en [mantener en pie la ciudad](#depositar-dinero-en-la-ciudad)
<details markdown="block">
  <summary>
	<strong>Comando(s) y ejemplo(s)</strong>
  </summary>

{: .comando}
> - `/t new nombreDeCiudad`

{: .ejemplos}
> - `/t new MiGranCiudad`
> - `/t new CiudadGótica`
> - `/t new Madrid`
</details>
---

## Depositar dinero en la ciudad
Varias acciones de ciudad requieren dinero, desde el mantenimiento diario de la ciudad (para que no caiga en ruinas) hasta el reclamo de nuevos terrenos, por lo que antes que nada, tendrás que depositar dinero en la ciudad, para esto puedes usar el comando `/t deposit cantidad` para depositar dinero de tu cuenta personal al banco de la ciudad, por ejemplo `/t deposit 1000` depositará $1,000 en el banco de tu ciudad y reducirá $1,000 de tu dinero personal.

Algunas cosas para las que puedes usar el dinero del banco de la ciudad son:
- **Mantener la ciudad en pie**
  - Esto tiene un costo diario, este depende del tamaño de tu ciudad, puedes verlo con `/towny prices` o `/t` (lo cual te muestra la información de tu ciudad actual).
- [Reclamar más terreno](#reclamar-más-terreno)
- Mantener tu ciudad en estado de paz/neutralidad.

<details markdown="block">
  <summary>
	<strong>Comando(s) y ejemplo(s)</strong>
  </summary>

{: .comando}
> - `/t deposit cantidad`

{: .ejemplo}
> Imaginemos que tu **banco tiene $0.00** y **tu cuenta tiene $1,500**:
>  1. Usas el comando `/t deposit 1000`
>  - El banco de la ciudad ahora tiene **$1,000**
>  - Tu cuenta personal ahora tiene **$500**
</details>
---

## Invitar a nuevos ciudadanos
Towny es una modalidad hecha para jugar con amigos (aunque realmente no necesitas amigos antes de entrar, haz amigos aquí y conquisten el mundo juntos c; ), si quieres invitar a alguien a tu ciudad usa el comando `/t add usuario`, una vez que tu uses este comando, al usuario le llegará un mensaje al chat diciéndole que le invitaste a tu ciudad, para más información sobre eso, mira la sección sobre [cómo unirse a una ciudad]({% link docs/towny/towny_resident.md %}#unirse-a-una-ciudad).

¿Invitaste a alguien por error a tu ciudad? No te preocupes, puedes eliminar la invitación usando el mismo comando, pero agregando un `-` antes del nombre del usuario (`/t add -usuario`)
<details markdown="block">
  <summary>
	<strong>Comando(s) y ejemplo(s)</strong>
  </summary>
  
{: .comandos}
> - `/t add usuario` - Para invitar a un usuario a tu ciudad
> - `/t add -usuario` - Para cancelar la invitación de un usuario

{: .ejemplos}
> - Para invitar a JuanitoGamer: `/t add JuanitoGamer`
> - Ya no quieres invitar a JuanitoGamer: `/t add -JuanitoGamer`
</details>
---

## Reclamar más terreno
Una vez que tienes tu ciudad creada, puedes reclamar nuevos chunks con el comando `/t claim` mientras estás parad@ en la plot que quieres reclamar (para más info acerca de las plots, mira [este artículo de nuestra wiki]({% link docs/towny/towny_plots.md %}))
<details markdown="block">
  <summary>
	<strong>Comando(s) y ejemplo(s)</strong>
  </summary>
  
{: .comando}
> - `/t claim`

{: .ejemplo}
> - Acabas de crear tu ciudad, caminas 16 bloques para adelante y usas el comando `/t claim`, ¡felicidades! tu ciudad ahora tiene 2 chunks :D
</details>
---

## Sacar a alguien de tu ciudad
Nunca falta el usuario molesto que hace cosas que no quieres en tu ciudad, no te deja opción, hay que sacarlo.
Para sacar a alguien de tu ciudad usa el comando `/t kick usuario` y listo, ¡adiós molestias!
<details markdown="block">
  <summary>
	<strong>Comando(s) y ejemplo(s)</strong>
  </summary>
  
{: .comando}
> - `/t kick usuario`

{: .ejemplo}
> - `/t kick 0Key_MC` - Sacará a *0Key_MC* de tu ciudad, pero solo si es miembro de ella... obviamente.
</details>