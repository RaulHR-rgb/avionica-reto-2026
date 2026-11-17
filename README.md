# Aviónica AAIAQ - Reto de Reclutamiento OTOÑO 2026

Repositorio oficial para la **Ruta 2: Diseño de hardware y acondicionamiento de señal** del proceso de reclutamiento de la División de Aviónica de la AAIAQ.

## Descripción del Proyecto
Diseño y simulación analógica de la etapa de acondicionamiento de señal para la computadora de vuelo, enfocada en dos módulos principales:
1. **Filtro Anti-Aliasing Pasa-Bajas:** Filtro Sallen-Key de 2.° orden (respuesta Butterworth, $f_c = 150\text{ Hz}$) para eliminar ruido eléctrico de alta frecuencia antes del muestreo del ADC a $1\text{ kHz}$.
2. **Monitor de Voltaje de Batería:** Divisor de voltaje seguro para supervisar una batería LiPo 2S ($6.0\text{ V} - 8.4\text{ V}$) adaptada al rango de entrada de $0 - 3.3\text{ V}$ de un microcontrolador.

## Herramientas y Versiones Usadas
* **Simulador:** LTspice (Simulaciones AC / Bode y Transitorias)[cite: 3]
* **Diseño Esquemático:** KiCad (Esquemático formal con desacoplo y etiquetas de red)[cite: 4]
* **Documentación:** LaTeX (Reporte técnico estructurado en Overleaf)[cite: 2]
* **Control de Versiones:** Git y GitHub[cite: 2]

## Estructura del Repositorio
* `src/`: Archivos fuente de esquemáticos y simulaciones en LTspice/KiCad[cite: 2, 5].
* `docs/`: Código fuente (`.tex`) y PDF del reporte técnico final[cite: 2, 5].
* `media/`: Gráficas de Bode, respuestas transitorias e imágenes de soporte[cite: 2, 5].

## Autor
* **Nombre:** Raúl Heredia Ramírez[cite: 6]
* **Carrera:** Licenciatura en Tecnología (UNAM)