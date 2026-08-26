# CampusHustles

Proyecto desarrollado en **Unreal Engine 5** utilizando **Blueprints**.

## Configuración

Este proyecto utiliza **Git LFS (Large File Storage)** para manejar los archivos binarios de Unreal Engine, principalmente:

* `.uasset` — Blueprints, materiales, texturas, meshes, etc.
* `.umap` — Mapas y niveles.

### Antes de clonar el proyecto

Cada miembro del equipo debe tener **Git LFS** instalado.

Una vez instalado, ejecutar:

```bash
git lfs install
```

Luego pueden clonar el repositorio normalmente:

```bash
git clone https://github.com/sebas3261/CampusHustles.git
```

> No es necesario ejecutar `git lfs track`. El repositorio ya contiene la configuración necesaria en `.gitattributes`.

## Workflow

Para trabajar normalmente:

```bash
git pull
git add .
git commit -m "Descripción del cambio"
git push
```

Git LFS se encargará automáticamente de los archivos de Unreal.
