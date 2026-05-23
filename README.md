# Tesis Magíster — Route Choice Modelling

**Modelamiento y clasificación de estrategias de elección de rutas en el transporte público de Santiago**

Repositorio de mi tesis para optar al título de Ingeniero Civil Matemático y al grado de Magíster en Ciencia de Datos de la Universidad de Chile.

Para ver Carta Gantt del estado de avance de mi tesis: https://app.clickup.com/90132761350/v/li/901322549474

---

## Estructura del repositorio

```
.
├── src/          # Código fuente principal (modelos, utilidades, etc.)
├── notebooks/    # Jupyter notebooks de exploración y prototipos
├── data/
│   ├── raw/      # Datos crudos (ignorados por git)
│   └── processed/# Datos procesados (ignorados por git)
├── docs/         # Documentación general del proyecto
├── papers/       # Papers y material bibliográfico en PDF
├── thesis/       # Borrador de tesis: capítulos, figuras, etc.
├── results/      # Salidas: tablas, métricas, modelos entrenados, etc.
├── scripts/      # Scripts de ejecución, ETL y utilidades
└── references/   # Links, citas, notas y bibliografía
```

> **Nota:** El contenido de `data/` está completamente excluido del control de versiones (ver `.gitignore`).  
> Los archivos `.gitkeep` en `data/raw/` y `data/processed/` aseguran que las carpetas sean visibles en el repositorio.

---

## Cómo ejecutar

> *Placeholder — completar cuando el entorno esté listo.*

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/sebastianacunau/tesis_magister_route_choice_modelling.git
   cd tesis_magister_route_choice_modelling
   ```

2. Crear y activar un entorno virtual:
   ```bash
   python -m venv .venv
   source .venv/bin/activate   # Windows: .venv\Scripts\activate
   ```

3. Instalar dependencias:
   ```bash
   pip install -r requirements.txt
   ```

4. Ejecutar los notebooks:
   ```bash
   jupyter lab
   ```

---

## Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).
