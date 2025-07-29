## 💪 Cookiecutter Data Science Template

Una plantilla profesional y personalizable para iniciar proyectos de ciencia de datos de manera estructurada, clara y reproducible. Basada en las mejores prácticas del ecosistema Python y diseñada para facilitar el trabajo en equipo y el control de versiones.

---

### 🚀 Características

- Estructura de proyecto basada en estándares
- Integración con Git y control de versiones
- Soporte para entornos virtuales con `conda`
- Archivo `environment.yml` para instalación de dependencias
- Opciones de licencias: MIT, Apache 2.0, GPLv3
- Carpeta `notebooks/` para experimentación con Jupyter
- Carpeta `src/` para código modular y reutilizable
- README inicial profesional
- Preconfiguración para documentación y distribución

---

### 📦 Estructura del proyecto generado

```
{{ cookiecutter.project_name }}/
│
├── data/
│   ├── raw/               # Datos originales (no modificados)
│   ├── processed/         # Datos listos para análisis o modelado
│
├── notebooks/             # Jupyter Notebooks para exploración y desarrollo
├── src/                   # Código fuente del proyecto
│   └── __init__.py
│
├── tests/                 # Pruebas del proyecto
├── environment.yml        # Dependencias de Conda
├── LICENSE
├── .gitignore
└── README.md
```

---

### 🛠️ Cómo usar esta plantilla

1. Instala Cookiecutter:
   ```bash
   pip install cookiecutter
   ```

2. Crea tu nuevo proyecto:
   ```bash
   cookiecutter https://github.com/{{ cookiecutter.tu_usuario }}/cookiecutter-data-science-template
   ```

3. Sigue las instrucciones interactivas para configurar tu nuevo proyecto.

---

### 📋 Licencia

Este repositorio y plantilla están disponibles bajo la licencia elegida en el proceso de generación (MIT, Apache 2.0 o GPLv3). Puedes ver los términos completos en el archivo `LICENSE` del proyecto generado.

---

### ✍️ Autor

Desarrollado por {{ cookiecutter.author_name }}