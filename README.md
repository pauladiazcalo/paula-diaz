# 🌐 EFDI Website Template

Este es un template para el repositorio personal de los estudiantes durante la **Especialización en Fabricación Digital e Innovación (EFDI - UTEC & FAB LAB BARCELONA)**.

---

## 📥 Requisitos previos

Antes de empezar, asegúrate de tener instalados:

- **Git** → [Descargar Git](https://git-scm.com/downloads)
- **Python 3** → [Descargar Python](https://www.python.org/downloads/)

---

## 🔍 Verificar instalaciones

En tu terminal (Mac/Linux) o en PowerShell (Windows), ejecuta:

```bash
git --version
python --version
```

Deberías ver un número de versión para cada uno.
Ejemplo:

```
git version 2.46.0
Python 3.11.6
```

---

## 🔄 Actualizar `pip` (gestor de paquetes de Python)

```bash
python -m pip install --upgrade pip
```

---

## 📦 Instalar MkDocs (si no lo tienes instalado)

En caso de que MkDocs no esté disponible en tu sistema, instálalo con:

```bash
pip install mkdocs mkdocs-material
```

Esto instalará MkDocs y el tema Material, necesarios para este proyecto.

---

## 📂 Clonar el repositorio

Ejecuta:

```bash
git clone git@github.com:fablabbcn/efdi-template.git
cd efdi-template
```

---

## 📦 Instalar dependencias del proyecto

Dentro de la carpeta clonada:

```bash
pip install -r requirements.txt
```

Esto instalará **MkDocs**, el tema `mkdocs-material` y los plugins necesarios.

---

## ▶️ Levantar MkDocs en local

Para ver la documentación en tu navegador (servidor local):

```bash
mkdocs serve
```

👉 Abre en tu navegadobash

r: [http://127.0.0.1:8000](http://127.0.0.1:8000)

---

## 🏗️ Generar el sitio estático

Para compilar la documentación y generar el sitio en la carpeta `site/`:

```bash
mkdocs build
```

El contenido dentro de `site/` es el que se publica en **GitHub Pages**.

---

## 🔗 Recursos útiles

- [Documentación del curso en Moodle](https://ev1.utec.edu.uy/moodle/course/view.php?id=15375&section=1#tabs-tree-start)
- [MkDocs — Documentación oficial](https://www.mkdocs.org/)
- [Material for MkDocs — Tema oficial](https://squidfunk.github.io/mkdocs-material/)
- [Comandos - GIT](https://education.github.com/git-cheat-sheet-education.pdf)

---

## 🚀 Demo del template

Puedes visitar la demo del template aquí:
👉 [https://mathira.github.io/efdi-template/](https://mathira.github.io/efdi-template/)
