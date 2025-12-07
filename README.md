**Conclusión Final**

Los tres modelos evaluados muestran buen desempeño al ajustar la relación cuadrática del dataset.
El modelo analítico obtiene el mejor equilibrio entre simplicidad y precisión, logrando un MSE bajo y un R² cercano a 1.
El modelo de descenso por gradiente alcanza resultados similares, demostrando que puede aproximar correctamente el modelo analítico cuando la tasa de aprendizaje y el número de iteraciones están bien ajustados.

El MLP con 10 neuronas tiene menor capacidad de ajuste y pierde parte de la curvatura.
El MLP de 50 neuronas proporciona un ajuste muy bueno, comparable al modelo analítico.
El MLP de 1000 neuronas sobreajusta los datos: logra un R² muy alto pero genera curvas no naturales fuera del rango observado.

En general, el mejor modelo para este problema fue el analítico y el MLP con 50 neuronas, mientras que el MLP de 1000 neuronas evidencia sobreajuste.
Este ejercicio permitió comprender las diferencias entre métodos estadísticos clásicos, optimización numérica y modelos neuronales.
