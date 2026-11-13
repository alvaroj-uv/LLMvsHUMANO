# Panel de expertos — instrumento de marcaje (v3, 2026-11-09)

Hosting del instrumento HTML del panel (marco 2,085 párrafos, muestra n=92, seed 2026110903).

- `index.html` — portal con un botón por experto (A–G).
- `instrumento_panel_experto_{A..E}.html` — instrumentos individuales (asignaciones congeladas, hash ASIG_SHA verificado).
- Expertos F y G incluidos como panel extendido (reserva activable).

El guardado de respuestas es local al navegador del experto (localStorage). La sincronización a base de datos en línea (Supabase) está en preparación; el respaldo JSON descargable sigue siendo el artefacto oficial.
