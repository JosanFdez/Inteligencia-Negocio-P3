# Inteligencia-Negocio-P3
Asignatura Inteligencia de Negocio practica 3 Algoritmos de Regresion

# Competición Kaggle - Predicción de Precios de Coches Usados

## Descripción General

Este proyecto es parte de la asignatura de **Inteligencia de Negocio** y se centra en la predicción de precios de coches usados mediante técnicas de aprendizaje supervisado. A través de esta competición de Kaggle, se han aplicado múltiples algoritmos de regresión para analizar datos categóricos y numéricos, optimizando modelos para lograr un rendimiento sobresaliente.

El objetivo principal fue entrenar modelos robustos que minimizaran el error cuadrático medio (RMSE) en el conjunto de validación, utilizando herramientas modernas de aprendizaje automático.

---

## Estructura del Proyecto

### Tabla de Resultados
Se realizaron 10 pruebas principales con los siguientes modelos y configuraciones:

| Prueba | Algoritmo       | Private Score | Public Score | RMSE   | Notas                      |
|--------|-----------------|---------------|--------------|--------|----------------------------|
| 1      | Decision Tree   | 103127.4581   | 123359.3895  | 4938.9861 | Parámetros por defecto     |
| 2      | Random Forest   | 64120.9060    | 73274.0232   | 72446.1059 | Hiperparámetros iniciales  |
| 3      | Random Forest   | 64037.32882   | 73222.9175   | 70293.3110 | Ajustes avanzados          |
| 4      | LightGBM        | 63427.0589    | 72620.8032   | 70213.1967 | Boosting inicial           |
| 5      | LightGBM        | 63458.8310    | 72566.6555   | 69618.7686 | Configuración optimizada   |
| 6      | XGBoost         | 65248.9026    | 73555.6484   | 58324.0853 | Boosting adicional         |
| 7      | H2O AutoML      | 63208.8047    | 72334.6425   | 72426.34  | Configuración estándar     |
| 8      | H2O AutoML      | 63194.9201    | 72358.5671   | 72306.23  | Exploración extendida      |
| 9      | CatBoost        | 63450.6778    | 72649.2229   | 71014.2782 | Soporte de categóricas     |
| 10     | ElasticNet      | 65732.4102    | 74677.2267   | 74814.1513 | Regularización lineal      |

---

## Tecnologías y Herramientas Utilizadas

- **Plataformas:**
  - Kaggle (Competición: Playground Series - Season 4, Episode 9)
- **Librerías:**
  - Scikit-learn
  - LightGBM
  - XGBoost
  - H2O AutoML
  - CatBoost
- **Entorno de Trabajo:**
  - Jupyter Notebooks
  - Python 3.x

---

## Modelos y Pruebas Destacadas

1. **LightGBM**: Destacó por su eficiencia y capacidad para manejar datos grandes y relaciones complejas, obteniendo algunos de los mejores resultados.
2. **H2O AutoML**: Logró resultados consistentes con un enfoque automatizado, facilitando la búsqueda de configuraciones óptimas en tiempo extendido.
3. **CatBoost**: Ofreció un excelente manejo de variables categóricas, destacando por su facilidad de uso y resultados competitivos.

---

## Métricas de Evaluación

- **RMSE (Root Mean Squared Error):** Principal métrica para evaluar la precisión de los modelos.
- **Private y Public Score:** Comparaciones en la tabla de clasificación de Kaggle.

---

## Propuesta Final

El modelo final seleccionado fue **H2O AutoML** con un tiempo extendido de 20,000 segundos, dado su rendimiento consistente y capacidad de exploración automática. Este enfoque permitió obtener el mejor equilibrio entre precisión y generalización.

---

## Referencias

1. [Scikit-learn Documentation](https://scikit-learn.org/)
2. [LightGBM GitHub](https://github.com/microsoft/LightGBM)
3. [XGBoost Paper](https://doi.org/10.1145/2939672.2939785)
4. [H2O AutoML](https://www.h2o.ai/)
5. [CatBoost Documentation](https://catboost.ai/)

---

## Contribuciones

Las contribuciones son bienvenidas. Si deseas colaborar:
1. Haz un fork del repositorio.
2. Realiza los cambios necesarios.
3. Envía un pull request detallando las modificaciones.

---

## Licencia

Este proyecto está licenciado bajo la [MIT License](LICENSE).
