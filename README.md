# Simulador del FNES: cooperativa de vivienda

Calculadora web de una sola página para contestar una pregunta concreta: ¿nos alcanza para una cooperativa de vivienda estudiantil con el Fondo Nacional de Economía Social (FNES)?

**Ver el simulador:** https://egutierrezcr.github.io/simulador-fnes/

## Qué muestra

- Cuánto tendría que pagar cada cuarto al mes.
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

Se adapta al tema claro u oscuro del sistema; no trae botón para cambiarlo.

## Licencia

MIT; ver [LICENSE](LICENSE).
