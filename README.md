# Actividad final del primer corte - Sistemas Inteligentes I

## Antes de comenzar

Para trabajar con los notebooks se recomienda:

- Instalar `uv`, que administrará Python, el entorno del proyecto y sus dependencias.
- Instalar **Visual Studio Code** con las extensiones **Python** y **Jupyter** de Microsoft, o utilizar Jupyter Notebook/JupyterLab.
- Los notebooks utilizan principalmente librerías estándar de Python; `matplotlib` se emplea para las gráficas.

## Integrantes

1. Ana Isabela Suarez
2. Santiago Silva
3. Juan Diego Henao

## Presentación

En esta actividad se desarrollan y analizan técnicas de búsqueda utilizadas en Inteligencia Artificial. Se estudian algoritmos de búsqueda no informada, búsqueda informada y búsqueda adversarial, implementando cada método, ejecutando experimentos y comparando sus resultados.

La entrega corresponde al desarrollo de los talleres propuestos al final de los notebooks trabajados durante las clases. Las respuestas conceptuales deben aparecer en celdas Markdown y el código debe conservarse ejecutado junto con sus resultados.

## Notebooks incluidos

| Notebook | Tema |
| --- | --- |
| `Resolucion_Problemas_Busqueda_NoInformada.ipynb` | Búsqueda no informada: BFS y DFS |
| `Resolucion_Problemas_Busqueda_Informada.ipynb` | Búsqueda informada: Costo Uniforme, A* y Beam Search |
| `Minimax.ipynb` | Búsqueda adversarial: algoritmo Minimax |
| `Poda_Alfa_Beta.ipynb` | Búsqueda adversarial: poda Alfa-Beta |

## Cómo ejecutar el trabajo

1. Clonar el repositorio y ubicarse en su carpeta:

	```bash
	git clone https://github.com/diego-juan3112/actividad-final-primer-corte-sistemas-inteligentes-1.git
	cd actividad-final-primer-corte-sistemas-inteligentes-1
	```

2. Instalar Python 3.11 y crear el entorno del proyecto con esa versión:

	```bash
	uv python install 3.11
	uv venv --python 3.11
	```

3. Activar el entorno en Windows PowerShell:

	```powershell
	.\.venv\Scripts\Activate.ps1
	```

4. Instalar las dependencias del repositorio:

	```bash
	uv pip install -r requirements.txt
	```

5. Abrir los cuatro archivos `.ipynb` en VS Code y seleccionar el kernel `.venv (Python 3.11)`.
6. Ejecutar todas las celdas en orden.
7. Verificar que los notebooks no presenten errores y que conserven las salidas y gráficas obtenidas.
