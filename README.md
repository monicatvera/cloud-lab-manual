# Master Front End XVII - Módulo 7 - Cloud - Laboratorio

## Modulo Cloud - Laboratorio

### Básico

1. Desplegar en Github Pages de forma manual:

   - Tenemos un repo en Github (el repo tiene que ser público)

   [https://github.com/monicatvera/cloud-lab-manual](https://github.com/monicatvera/cloud-lab-manual)

   - Queremos desplegar una app.
   - Realizar el despliegue manual.

#### Para poder desplegar manualmente en Github Pages:

- Hacer la build

```bash
npm run build
```

- Crear rama llamada **gh-pages**

```bash
git branch gh-pages
```

- Cambiar a la rama **gh-pages**

```bash
git checkout gh-pages
```

- En la rama **gh-pages** copiamos únicamente los ficheros del bundle (los que están dentro de la carpeta dist)
- Cambiar en index.html de la build la ruta a los assets. De forma relativa al index.html
- Al hacer push a la rama **gh-pages** despliega la aplicación

```bash
git add .
git push
```

Aplicación desplegada de forma manual en Github Pages: [https://monicatvera.github.io/cloud-lab-manual/](https://monicatvera.github.io/cloud-lab-manual/)
