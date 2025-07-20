# gh-deployment-workflow

Este proyecto demuestra la implementación de un flujo de trabajo de integración y despliegue continuo (CI/CD) utilizando GitHub Actions para desplegar un sitio web estático en GitHub Pages.

## Descripción

El proyecto consiste en un sitio web estático simple que se despliega automáticamente en GitHub Pages cada vez que se realiza un cambio en el archivo `index.html` en la rama principal (main).

## Características

- Despliegue automático a GitHub Pages
- Activación del flujo de trabajo solo cuando se modifica `index.html`
- Página web simple con el mensaje "Hello, GitHub Actions!"

## Estructura del Proyecto

```
gh-deployment-workflow/
├── .github/
│   └── workflows/
│       └── deploy.yml
├── index.html
└── README.md
```

## Cómo Funciona

1. Cuando se realiza un push a la rama main que incluye cambios en `index.html`
2. GitHub Actions detecta el cambio y ejecuta el flujo de trabajo definido en `deploy.yml`
3. El sitio web se despliega automáticamente en GitHub Pages
4. Los cambios son visibles en https://<username>.github.io/gh-deployment-workflow/

## Tecnologías Utilizadas

- GitHub Actions
- GitHub Pages
- HTML/CSS
