# Asteci

Aplicacion web en React para consultar condiciones atmosfericas de Mexico a partir de la API publica de datos.gob.mx. Los resultados se muestran en una tabla paginada con datos de ubicacion, temperatura, humedad, viento y precipitacion.

## Requisitos

- Node.js
- npm
- Conexion a Internet para consultar la API

## Instalacion y ejecucion

```bash
npm install
npm start
```

Create React App inicia el servidor de desarrollo en [http://localhost:3000](http://localhost:3000).

## Otros comandos

```bash
npm test
npm run build
```

La aplicacion consulta `https://api.datos.gob.mx/v1/condiciones-atmosfericas` en paginas de diez registros.
