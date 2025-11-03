# Modelado y Validación Experimental de Filtros de Control (MATLAB & Hardware)

**Estado del Proyecto:** Simulación teórica (MATLAB) y validación experimental (Hardware/Osciloscopio) completadas.

---

## 1. Resumen del Proyecto

Este proyecto integral demuestra mi capacidad para modelar sistemas de control y validar su comportamiento en hardware. Se diseñó, simuló y midió un **Filtro Pasa-Bajas RC de Primer Orden** para comprender y mitigar el ruido de alta frecuencia, una habilidad crítica en sistemas de potencia y control.

La fase inicial consistió en el cálculo teórico y el modelado en MATLAB. La segunda fase se centró en la **implementación del circuito físico** y la medición de la respuesta de frecuencia utilizando un osciloscopio, comparando las señales obtenidas con las curvas predichas por la simulación.

### ➡️ Informes Técnicos Completos

* **Parte 1: Análisis Teórico y Simulación (MATLAB)**
    * **[Ver Reporte Tarea 6 (Simulación)](./250512_341838_JA_T06.pdf)**
* **Parte 2: Implementación y Validación Experimental (Hardware)**
    * **[Ver Reporte Práctica 4 (Hardware)](./250518_A341838_JARH_P4.pdf)**

---

## 2. Herramientas y Competencias Demostradas

* **Modelado y Programación:** Uso avanzado de **MATLAB** para calcular funciones de transferencia H(s), simular la respuesta en fase y ganancia, y generar gráficos de control.
* **Validación de Hardware:** Montaje del circuito RC y uso experto del **Osciloscopio** para medir las señales de entrada y salida, demostrando la atenuación de la señal de prueba (PWM) conforme aumenta la frecuencia.
* **Análisis de Sistemas:** Comprensión de cómo la ganancia cae a -3 dB y la fase a $-45^\circ$ en la frecuencia de corte ($f_c$).

**(Imagen de la Simulación en MATLAB)**
![Gráfico de Ganancia y Fase del Filtro RC en MATLAB](Img/Filtro_RC.jpg)

**(Imagen de la Medición en Osciloscopio)**
![Señal de salida medida en el Osciloscopio vs. Señal de entrada](Img/Osciloscopio_Resultados.jpg)
