Proyecto Coder - Series de Tiempo / Predicción de Ventas
==============================

El objetivo de este trabajo es poder implementar un algoritmo predictivo de machine learning que permita conocer de manera precisa las ventas mensuales futuras.

Organización del Proyecto
------------

    En este proyecto se trabajará con un Dataset provisto por Kaggle. En el siguiente link puede encontrarse el dataset: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce.

El problema específico radica en la posibilidad de contar con una proyección de ventas que permita tener una estimación de la rentabilidad del negocio y así definir estrategias comerciales para lograr una mejor atención al cliente, mejorar la administración de las sucursales y gestionar eficientes campañas de marketing.

Para el análisis de dicho dataset, se ha hecho una limpieza del mismo y se estableció como periodo de estudio el plazo que abarca desde 01/11/2016 hasta el 27/09/2018.

A su vez, se han implementado una serie de modelos aplicables a series de tiempo:

Modelo Arima, con la determinación de sus parametros, entrenamiento, analisis de la media constante y su varianza, y su modelo más óptimo.

Auto Arima

Modelo Sarima

Los mencionados modelos se han implementado para la proyección de ventas en forma diaria y semanal.

