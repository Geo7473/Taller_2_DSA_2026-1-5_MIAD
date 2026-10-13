# Tablero de pronóstico de producción energética

Taller 2 de *Despliegue de soluciones analíticas* (MIAD, Uniandes).

Tablero hecho con [Dash](https://dash.plotly.com/) que muestra la demanda
energética total de Austria por hora, según el portal ENTSO-E, junto con un
pronóstico de hasta 5 días.

## Contenido

- `app.py`: lógica y diseño del tablero.
- `datos_energia.csv`: datos históricos y pronóstico.
- `assets/`: hojas de estilo CSS.

## Ejecución local

```
pip install dash pandas
python app.py
```

Luego abrir http://127.0.0.1:8050 en el navegador.
