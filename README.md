# hello-world-docker
Ejemplo de Hola Mundo con Java y Docker

### Pre-requisitos 📋
Tener instalado Docker y algun editor de texto

```
docker version
```

### Instalación 🔧

Clonar el repositorio
```
git clone https://github.com/evertcode/hello-world-docker.git
```

Constuir la imagen
```
docker build -t helloworld .
```

Obtener IMAGEN_ID de **helloworld**
```
docker image
```

### Ejecutando las pruebas ⚙️

```
docker run IMAGEN_ID
```

## Licencia 📄

Este proyecto está bajo la Licencia (MIT) - mira el archivo [LICENSE.md](LICENSE.md) para detalles

