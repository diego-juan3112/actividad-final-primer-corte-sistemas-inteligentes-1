# Actividad final del primer corte — Sistemas Inteligentes I

## Integrantes

1.Santiago Silva Guarnizo
2. Ana Isabella Suárez Cardona
3. Juan Diego Henao Quintero

## Descripción

Este repositorio reúne los talleres de búsqueda desarrollados para la actividad final del primer corte de Sistemas Inteligentes I. Cada solución contiene la implementación, las respuestas conceptuales en celdas Markdown, los experimentos y los resultados obtenidos al ejecutar las celdas en orden.

La actividad solicita cubrir los siguientes temas:

1. Búsqueda no informada: BFS y DFS.
2. Búsqueda informada.
3. Búsqueda adversarial: Minimax.

## Notebooks incluidos

| Taller | Archivo de solución | Material de apoyo |
| --- | --- | --- |
| Búsqueda no informada: BFS y DFS | `1_Busqueda_no_informad_BFS_DFS/Solucion.ipynb` | `1_Busqueda_no_informad_BFS_DFS/Resolucion_Problemas_Busqueda_NoInformada.ipynb` |
| Búsqueda informada | `2_Busqueda_informada/Solucion.ipynb` | `2_Busqueda_informada/Resolucion_Problemas_Busqueda_Informada.ipynb` |
| Búsqueda adversarial: Minimax | `3_Busqueda_adversarial_Minimax/Solucion.ipynb` | `3_Busqueda_adversarial_Minimax/Resolucion_Minimax.ipynb` |

> **Importante:** el taller de poda Alfa–Beta es obligatorio para la entrega, pero no se tomara en cuenta dado que no contiene taller, dejamos esta nota como recordatorio. 

## Requisitos

- Git.
- [uv](https://docs.astral.sh/uv/) instalado. `uv` descarga Python, crea el entorno y administra las dependencias.
- Visual Studio Code con las extensiones **Python** y **Jupyter**, o Jupyter Notebook/JupyterLab.

Las dependencias están definidas en `requirements.txt`: `jupyter`, `ipykernel` y `matplotlib`.

## Ejecución en Linux

```bash
git clone https://github.com/diego-juan3112/actividad-final-primer-corte-sistemas-inteligentes-1.git
cd actividad-final-primer-corte-sistemas-inteligentes-1
uv venv --python 3.11
uv pip install -r requirements.txt
uv run jupyter lab
```

## Ejecución en Windows (PowerShell)

```powershell
git clone https://github.com/diego-juan3112/actividad-final-primer-corte-sistemas-inteligentes-1.git
cd actividad-final-primer-corte-sistemas-inteligentes-1
uv venv --python 3.11
uv pip install -r requirements.txt
uv run jupyter lab
```

Luego abra los notebooks de solución, seleccione el intérprete o kernel de `.venv` y ejecute todas las celdas en orden. Verifique que las salidas y gráficas queden guardadas antes de realizar la entrega.

## Uso de IA generativa

| Herramienta | Propósito | Parte en la que se empleó | Responsable |
| --- | --- | --- | --- |
| OpenAI Codex | Organización y redacción del README | Documentación del repositorio; no se declara uso en la implementación de los algoritmos. | Ana Isa |
|Github Copilot | apoyo para revisar la estructura del taller, sugerir casos de prueba y detectar inconsistencias durante la ejecución del notebook. | organización inicial de las celdas, revisión de pruebas y apoyo en la redacción de algunas explicaciones. | Santiago Silva |

## Lista de verificación de entrega

- [ ] El repositorio es accesible mediante el enlace entregado.
- [ ] Están incluidos y ejecutados los tres notebooks requeridos.
- [ ] Las respuestas conceptuales están en celdas Markdown.
- [ ] El código, resultados y gráficas están visibles en los notebooks.
- [ ] El README está actualizado y corresponde a la versión definitiva.
- [ ] La entrega se realiza antes del viernes 25 de septiembre de 2026 a las 6:00 p. m.
