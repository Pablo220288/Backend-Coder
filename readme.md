<div align="center">
<img src="./public/img/apibooks.png"/ alt="ApiBooks">
</div>

_Bienvenidos a mi proyecto BackEnd ._

_El mismo consiste en una API de consulta de los libros mas reconocidos del medio, los generos mas variados y los mejores autores._

## Comenzando 馃殌

- Descargue este c贸digo fuente en un directorio de trabajo, aseg煤rese de usar la bandera `--recurse-submodules` para clonar tambi茅n nuestros subm贸dulos.

### Pre-requisitos 馃搵

- Instale los requisitos usando npm:

  ```sh
  npm install
  # Esto instalar谩 todos los paquetes y bibliotecas necesarios para usar ApiBooks
  ```

### Instalaci贸n 馃敡

- Ejecute el servidor usando el siguiente comando
  ```sh
  npm run dev
      # Esto ejecutara el servicor en el puerto 8080
  ```

Visite localhost:8080/api/products para ver la API en ejecuci贸n.

Recibiras una respuesta como la siguiente:

```sh
  [
    {
      "title": "Orgullo y Prejuicio",
      "description": "Libro Romance",
      "price": 1500,
      "status": true,
      "category": "Romance",
      "thumbnail": [
        "https://Orgullo-y-prejuicio-jane-austen-1.   jpeg",
        "https://Orgullo-y-prejuicio-jane-austen-2.   jpeg"
      ],
      "code": "abc121",
      "stock": 5,
      "id": "5ef92557d80743068999ca0e0c436f5c"
    },
    {},{},
  ]
```

## Ejecutando las pruebas 鈿欙笍

- Para filtar los items por su ID solo necesitas agregar "/" y el numero de ID a la consulta del navegaros
  ```sh
  http://localhost:8080/api/products/5ef92557d80743068999ca0e0c436f5c
      # Este es un ejemplo de la consulta por ID
  ```
- Es posible limitar la cantidad de resultados generando una query de nombre "limit"
  ```sh
  http://localhost:8080/api/products?limit=3
      # Este es un ejemplo de la consulta limitada a 3 resultados
  ```

### Analice las pruebas end-to-end 馃敥

_Explica que verifican estas pruebas y por qu茅_

```
Da un ejemplo
```

### Y las pruebas de estilo de codificaci贸n 鈱笍

_Explica que verifican estas pruebas y por qu茅_

```
Da un ejemplo
```

## Despliegue 馃摝

_Agrega notas adicionales sobre como hacer deploy_

## Construido con 馃洜锔?

_Usamos las mejores Herramientas_

- [React](http://www.dropwizard.io/1.0.2/docs/) - El framework web usado
- [Node.JS](https://maven.apache.org/) - Manejador de dependencias
- [Handlebars](https://rometools.github.io/rome/) - Usado para generar RSS

## Contribuyendo 馃枃锔?

Por favor lee el [CONTRIBUTING.md](https://gist.github.com/villanuevand/xxxxxx) para detalles de nuestro c贸digo de conducta, y el proceso para enviarnos pull requests.

## Wiki 馃摉

Puedes encontrar mucho m谩s de c贸mo utilizar este proyecto en nuestra [Wiki](https://github.com/tu/proyecto/wiki)

## Versionado 馃搶

Usamos [SemVer](http://semver.org/) para el versionado. Para todas las versiones disponibles, mira los [tags en este repositorio](https://github.com/tu/proyecto/tags).

## Autores 鉁掞笍

_Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios_

- **Andr茅s Villanueva** - _Trabajo Inicial_ - [villanuevand](https://github.com/villanuevand)
- **Fulanito Detal** - _Documentaci贸n_ - [fulanitodetal](#fulanito-de-tal)

Tambi茅n puedes mirar la lista de todos los [contribuyentes](https://github.com/your/project/contributors) qu铆enes han participado en este proyecto.

## Licencia 馃搫

Este proyecto est谩 bajo la Licencia (Tu Licencia) - mira el archivo [LICENSE.md](LICENSE.md) para detalles

## Expresiones de Gratitud 馃巵

- Comenta a otros sobre este proyecto 馃摙
- Invita una cerveza 馃嵑 o un caf茅 鈽? a alguien del equipo.
- Da las gracias p煤blicamente 馃.
- Dona con cripto a esta direcci贸n: `0xf253fc233333078436d111175e5a76a649890000`

---
