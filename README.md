# Sistema Barbería — DEMO

Demostración completa del sistema de gestión para barberías. Pensado para mostrar a clientes potenciales.

## Importante: entorno aislado

Este demo **NO se conecta a ninguna base de datos real**. Todos los datos (cobros, barberos, citas, gráficos) son de ejemplo y viven dentro de los propios archivos. Los cambios que se hagan durante una demostración se guardan **solo en el navegador de esa computadora** y nunca salen a ninguna nube.

## Contenido

- **index.html** — Menú principal para navegar durante la demostración.
- **bg17.html** — Caja y control: cobros, producción por barbero, nómina, gastos y gráficos históricos.
- **gar-ag.html** — Agenda del día, con recordatorio en pantalla al recibir una reserva.
- **reservar.html** — Página pública de reservas (lo que ve el cliente). Agenda directo, sin aprobación.

## Accesos

| Sección | Contraseña |
|---|---|
| Caja (bg17) | `demo` |
| Agenda (gar-ag) | `demo` |
| Admin (dentro de Caja) | `admin` |

## Reiniciar el demo

Desde el menú principal (index.html) hay un botón **"Reiniciar datos del demo"** que borra los cambios de la demostración y regresa todo a los datos originales de ejemplo.

## Publicar en línea

Los archivos son HTML estático: funcionan abriéndolos directo en el navegador, o publicados con GitHub Pages (Settings → Pages → rama main).
