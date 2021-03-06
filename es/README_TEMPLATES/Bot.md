<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://i.imgur.com/FxL5qM0.jpg" alt="Bot logo"></a>
</p>

<h3 align="center">Nombre del Bot</h3>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]()
  [![Platform](https://img.shields.io/badge/platform-reddit-orange.svg)](https://www.reddit.com/user/Wordbook_Bot)
  [![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
  [![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
  [![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> 馃 Unas cuantas lineas describiendo que hace el bot.
    <br>
</p>

## 馃摑 Tabla de contenido
- [馃摑 Tabla de contenido](#-tabla-de-contenido)
- [馃 Acerca de <a name = "about"> </a>](#-acerca-de--)
- [馃帴 Demostraci贸n <a name = "demo"> </a>](#-demostraci贸n--)
- [馃挱 C贸mo funciona <a name = "working"> </a>](#-c贸mo-funciona--)
- [馃巿 Uso <a name = "usage"> </a>](#-uso--)
  - [Ejemplo](#ejemplo)
- [馃弫 Comenzando <a name = "getting_started"> </a>](#-comenzando--)
  - [Requisitos previos](#requisitos-previos)
  - [Instalaci贸n](#instalaci贸n)
- [馃殌 Implementaci贸n de su propio bot <a name = "deployment"> </a>](#-implementaci贸n-de-su-propio-bot--)
- [鉀忥笍 Creado con <a name = "built_using"> </a>](#锔?-creado-con--)
- [鉁嶏笍 Autores <a name = "authors"> </a>](#锔?-autores--)
- [馃帀 Agradecimientos <a name = "acknowledgement"> </a>](#-agradecimientos--)

## 馃 Acerca de <a name = "about"> </a>

Escribe entre 1 y 2 p谩rrafos que describan el prop贸sito de tu bot.

## 馃帴 Demostraci贸n <a name = "demo"> </a>

![En funcionamiento](https://media.giphy.com/media/20NLMBm0BkUOwNljwv/giphy.gif)

## 馃挱 C贸mo funciona <a name = "working"> </a>

El bot primero extrae la palabra del comentario y luego busca definiciones de palabras, parte del discurso, ejemplo y fuente de la API del Diccionario Oxford.

Si la palabra no existe en el Diccionario Oxford, la API de Oxford devuelve una respuesta 404 en la que el bot intenta obtener resultados de la API del Diccionario Urbano.

El bot usa la API Pushshift para buscar comentarios, el m贸dulo PRAW para responder a los comentarios y Heroku como servidor.

Todo el bot est谩 escrito en Python 3.6

## 馃巿 Uso <a name = "usage"> </a>

Para usar el bot, escriba:

```
! dict palabra
```

La primera parte, es decir, "! Dict" ** no distingue entre may煤sculas y min煤sculas.

El bot le dar谩 la definici贸n de la palabra en el Diccionario Oxford (o Urban Dictionary, si la palabra no existe en el Diccionario Oxford) como respuesta a un comentario.

### Ejemplo

>! dict que es el amor

**Definici贸n:**

Beb茅, no me lastimes ~
No me hagas da帽o ~ no m谩s.

**Ejemplo:**

Amigo1: Bruh, 驴qu茅 es el amor?
Dude2: Cari帽o, no me hagas da帽o, no me hagas da帽o, 隆no m谩s!
Amigo1: 驴dafuq?

**Fuente:** <https://www.urbandictionary.com/define.php?term=what%20is%20love>

---

<sup> Bip boop. Soy un bot. Si hay alg煤n problema, comun铆quese con mi [Maestro](https://www.reddit.com/message/compose/?to=PositivePlayer1&subject=/u/Wordbook_Bot) </sup>

<sup> 驴Quieres hacer un bot de reddit similar? Echa un vistazo a: [GitHub](https://github.com/kylelobo/Reddit-Bot) </sup>

## 馃弫 Comenzando <a name = "getting_started"> </a>

Estas instrucciones le proporcionar谩n una copia del proyecto en funcionamiento en su m谩quina local con fines de desarrollo y prueba. Consulte [implementaci贸n](#implementaci贸n) para obtener notas sobre c贸mo implementar el proyecto en un sistema en vivo.

### Requisitos previos

Qu茅 necesita para instalar el software y c贸mo instalarlo.

```
Dar ejemplos
```

### Instalaci贸n

Una serie de ejemplos paso a paso que le indican c贸mo ejecutar un entorno de desarrollo.

Di cu谩l ser谩 el paso

```
Da el ejemplo
```

Y repetir

```
hasta que termine
```

Termine con un ejemplo de c贸mo sacar algunos datos del sistema o usarlos para una peque帽a demostraci贸n.

## 馃殌 Implementaci贸n de su propio bot <a name = "deployment"> </a>

Para ver un proyecto de ejemplo sobre c贸mo implementar su bot, consulte mi propia configuraci贸n:

+ **Heroku**: <https://github.com/kylelobo/Reddit-Bot#deploying_the_bot>

## 鉀忥笍 Creado con <a name = "built_using"> </a>

+ [PRAW](https://praw.readthedocs.io/en/latest/) - Envoltorio de API de Python Reddit
+ [Heroku](https://www.heroku.com/) - Plataforma de alojamiento SaaS

## 鉁嶏笍 Autores <a name = "authors"> </a>

- [@kylelobo](https://github.com/kylelobo) - Idea y trabajo inicial
- [@FanchiniRudolf](https://github.com/FanchiniRudolf) - Traducci贸n al espa帽ol

Consulte tambi茅n la lista de [contribuyentes](https://github.com/kylelobo/The-Documentation-Compendium/contributors) que participaron en este proyecto.

## 馃帀 Agradecimientos <a name = "acknowledgement"> </a>

- Apreciaci贸n para cualquier persona cuyo c贸digo se haya utilizado
- inspiraci贸n
- referencias
