# Monocuco
> Diccionario de palabras y frases costeñas.

<div align="center">
  <a href="monocuco-f4976.firebaseapp.com">
    <img src="/src/icon.jpg" alt="Monocuco" width="300px" />
  </a>
</div>

## Objetivo
Crear el más grande dataset de palabras y frases usadas en la Costa Caribe - Colombia.

## ¿Cómo contribuir?
Monocuco está desarrollada con React.js, si quieres proponer una mejora, arreglar algún problema o añadir nuevas palabras al diccionario realiza los siguientes pasos:

### Si eres desarrollador
1. Crea el fork
2. Crea una nueva rama con uno de estos nombres: fix (solucionar bug), feature (mejora) o new-word (añadir nueva palabra)
3. Puedes añadir la palabra de dos maneras:

**Usando el CLI (Nuevo!)**  
Ingresa a tu consola:
```bash
  npm run cli
```
Y luego ingresas la información en consola a medida que se vaya pidiendo:
```bash
? Palabra Jodido
? Significado Persona que está mal
? Sinónimos (separados por coma) salado
? Por favor, escribe un ejemplo por línea. Received
? ¿Cuál es tu nombre? Wilson Tovar
? ¿Cuál es el link de tu cuenta en GitHub? https://github.com/krthr

¡Nueva palabra agregada correctamente! ¡Gracias!
Ya puedes hacer commit y realizar el PR. ;)
```

**Editando archivo**  
Debes la entrada directamente en el archivo `src/data.json` siguiendo esta estructura:
```json
  "text": "Monocuco",
  "meaning": "Palabra utilizada para referirse a algo que está bien o es bonito. Figura del carnaval de barranquilla.",
  "synonyms": [],
  "examples": [
    "‘Con esta pinta nueva quedé monocuco’",
    "‘Mira, ahí viene bailando el monocuco’"
  ],
  "authors": [{
    "name": "Javier Valencia",
    "link": "https://github.com/jvalenciae"
  }]
```
6. Crea el pull request
7. Opcional: Añadate en la lista de contribuidores &#128526; (no cambies el orden)
8. Listo!

### Si no eres desarrollador
1. Envíame un email a [jsrd98@gmail.com](mailto:jsrd98@gmail.com) con la siguiente información:

- Palabra
- Significado
- Sinónimos (opcional)
- Ejemplos (máximo dos)
- Tu página personal, o algún link para que puedan buscarte
- Tu nombre

2. En el asunto coloca: Nueva palabra - Monocuco
3. Listo!

## Contribuidores
<table>
  <tr>
    <td align="center"><a href="https://github.com/sjdonado"><img src="https://avatars0.githubusercontent.com/u/27580836?s=460&v=4" width="460" alt="Juan Rodriguez"/><br /><sub><b>Juan Rodriguez</b></sub></a></td>
    <td align="center"><a href="https://github.com/krthr"><img src="https://avatars0.githubusercontent.com/u/18665740?s=460&v=4" width="460" alt="Wilson Tovar"/><br /><sub><b>Wilson Tovar</b></sub></a></td>
    <td align="center"><a href="https://github.com/jvalenciae"><img src="https://avatars0.githubusercontent.com/u/44078264?s=460&v=4" width="460" alt="Javier Valencia"/><br /><sub><b>Javier Valencia</b></sub></a></td>
    <td align="center"><a href="https://github.com/C9-LinkRs"><img src="https://avatars0.githubusercontent.com/u/23248296?s=460&v=4" width="460" alt="Johnny Villegas"/><br /><sub><b>Johnny Villegas</b></sub></a></td>
    <td align="center"><a href="https://github.com/fokobot"><img src="https://avatars0.githubusercontent.com/u/25647093?s=460&v=4" width="460" alt="fokobot"/><br /><sub><b>fokobot</b></sub></a></td>
    <td align="center"><a href="https://github.com/herasj"><img src="https://avatars0.githubusercontent.com/u/25647268?s=460&v=4" width="460" alt="Juan Rambal"/><br /><sub><b>Juan Rambal</b></sub></a></td>
    <td align="center"><a href="https://github.com/Yenniferh"><img src="https://avatars0.githubusercontent.com/u/19285706?s=460&v=4" width="460" alt="Yennifer Herrera"/><br /><sub><b>Yennifer Herrera</b></sub></a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/jaravad"><img src="https://avatars0.githubusercontent.com/u/30931849?s=460&v=4" width="460" alt="Jesus Santiago"/><br /><sub><b>Jesus Santiago</b></sub></a></td>
    <td align="center"><a href="https://github.com/oskhar1099"><img src="https://avatars0.githubusercontent.com/u/44534546?s=460&v=4" width="460" alt="Oskhar Arrieta"/><br /><sub><b>Oskhar Arrieta</b></sub></a></td>
    <td align="center"><a href="https://github.com/kristellu"><img src="https://avatars0.githubusercontent.com/u/28717626?s=460&v=4" width="460" alt="Kristell Urueta"/><br /><sub><b>Kristell Urueta</b></sub></a></td>
    <td align="center"><a href="https://github.com/juandavid716"><img src="https://avatars0.githubusercontent.com/u/42303342?s=460&v=4" width="460" alt="Juan Bojato"/><br /><sub><b>Juan Bojato</b></sub></a></td>
    <td align="center"><a href="https://github.com/pygabo"><img src="https://avatars0.githubusercontent.com/u/17889145?s=400&u=a25cac21223fb057416d6e3f4e2fc44afee7c6b4&v=4" width="460" alt="Jose Guzman"/><br /><sub><b>Jose Guzman</b></sub></a></td>
    <td align="center"><a href="https://github.com/Rafaell416"><img src="https://avatars0.githubusercontent.com/u/18080929?s=400" width="460" alt="Rafael Villarreal"/><br /><sub><b>Rafael Villarreal</b></sub></a></td>
    <td align="center"><a href="https://github.com/Isaiasdelahoz"><img src="https://avatars3.githubusercontent.com/u/25128103?s=460&u=3a44744203ab858fcda162b7e6037f3e79d6bdfe&v=4" width="460" alt="Isaias De la Hoz"/><br /><sub><b>Isaías De la Hoz</b></sub></a></td>
  </tr>
<table>

## Agradecimientos especiales
- Andres Urquina: Autor del icono [Ilustración Bailarina - Carnaval de Barranquilla, Colombia.](https://www.flickr.com/photos/andresurquina/16246891029)
