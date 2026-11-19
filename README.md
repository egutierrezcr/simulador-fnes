# ¿Nos alcanza para una cooperativa de vivienda?

Calculadora web de una sola página para contestar una pregunta concreta: ¿alcanza la plata para una cooperativa de vivienda estudiantil?

**Ver el simulador:** https://egutierrezcr.github.io/simulador-fnes/

## Qué muestra

- Si alcanza o no, en una línea, apenas abre la página.
- Cuánto tendría que pagar cada cuarto al mes.
- Cuánto se ahorraría quien vive ahí, al mes, al año y en una carrera de cuatro años.
- Por qué con más casas el costo por cuarto baja.
- Cuánta plata hay que juntar para comprar.
- Si el modelo aguanta 10 años.
- A dónde se va cada ₡100 que entra.
- Qué pasa si algo sale mal (ocupación baja, tasa más alta, gastos de más).
- La alternativa de arrancar alquilando una casa.
- Lo que entra y lo que sale cada mes, las reglas que no se pueden saltar y el detalle de números para quien quiera revisarlos.

## Supuestos

Los números son un escenario de trabajo, no una oferta de crédito. El préstamo se modela con el supuesto 2026 del INFOCOOP (6,25% a 20 años); las condiciones reales hay que preguntarlas. Los seguros, honorarios y gastos administrativos están como supuestos y hay que cotizarlos. Cada tarjeta indica su fuente o si es supuesto.

## Cómo correrlo

Es un solo archivo sin dependencias ni compilación. Abrir `index.html` en el navegador, o servirlo:

```bash
python -m http.server 8000
```

Trae tema claro y oscuro, con un control en la esquina para fijar uno o seguir el del sistema.

El botón "Copiar enlace" arma una dirección con los números que uno puso, para mandarla por WhatsApp y que el otro abra el mismo escenario.

## Diseño

Sigue la línea gráfica de My Intelligent System: Space Grotesk para títulos y cifras, Public Sans para el cuerpo, IBM Plex Mono para etiquetas y datos, tarjetas de borde fino sobre retícula de puntos.

## Firma

Emmanuel Gutiérrez, [egutierrezcr.github.io](https://egutierrezcr.github.io/).

## Licencia

MIT; ver [LICENSE](LICENSE).
