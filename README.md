# Documentación del Cuaderno Jupyter

## Propósito

Este cuaderno Jupyter está diseñado para extraer datos bursatiles de dos empresas utilizando yfinance y ejecutando un *webscraping* desde la página web para presentar la
información en tablas y por fin mostrar las gráficas de ambas empresas.

## Contenido

1. Definir una Función que Crea un Gráfico
2. Usar yfinance para Extraer Datos de Acciones
3. Usar Webscraping para Extraer Datos de Ingresos de Tesla
4. Usar yfinance para Extraer Datos de Acciones
5. Usar Webscraping para Extraer Datos de Ingresos de GME
6. Crear el Gráfico de Acciones de Tesla
7. Crear el Gráfico de Acciones de GameStop 

## Dependencias empleadas en este cuaderno

    - !pip install yfinance
    - !pip install bs4
    - !pip install nbformat
    - import yfinance as yf
    - import pandas as pd
    - import requests
    - from bs4 import BeautifulSoup
    - import plotly.graph_objects as go
    - from plotly.subplots import make_subplots
    - import warnings
