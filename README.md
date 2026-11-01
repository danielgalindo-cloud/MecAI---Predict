# MecAI Predict — preprototipo

Aplicación web de demostración para visualizar el concepto de mantenimiento predictivo en maquinaria metalmecánica.

## Importante

Todos los equipos, métricas, tendencias, alertas y recomendaciones son **datos simulados**. Esta aplicación no se conecta a sensores reales, no genera diagnósticos y no debe emplearse para decisiones de seguridad, operación o mantenimiento.

## Cómo abrirla localmente

1. Extrae el archivo ZIP (si aplica).
2. Abre la carpeta `mecai-predict`.
3. Haz doble clic en `index.html`, o arrástralo a una ventana de Chrome o Edge.
4. La aplicación funciona sin instalar nada. Para las gráficas interactivas, el navegador necesita conexión a internet la primera vez, pues Chart.js se carga desde su CDN.

## Módulos incluidos

- **Inicio:** resumen de equipos simulados, alertas y estado de flota.
- **Monitoreo:** selector de motor eléctrico, prensa hidráulica, dobladora de tubos, cortadora láser y compresor, con gráficas interactivas simuladas de vibración, temperatura y consumo energético.
- **Mantenimiento:** historial ficticio y recomendaciones orientativas.

## Archivos

- `index.html`: estructura e interfaz.
- `styles.css`: estilos responsive.
- `app.js`: navegación, datos de demostración y gráficas.
