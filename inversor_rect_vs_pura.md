# Diferencia entre inversor onda modificada(cuadrada) y onda pura

## Inversor

Conversor de DC / AC con caracteristicas en frecuencia y amplitud que deben ser constantes.

Tener en cuenta el tipo de entrada DC : -24, 12, 24, 48, 110, 220 DC.
Con salida monofasica de: 115, 127, 230, 254 Vac
O con salida trifasica: 200, 220, 400, 440 Vac.
Frecuencia de salida: 50, 60 400 Hz.

#### Mantenimiento:

- Sustitucion de modulos
- Reserva para configuración N+1
- Reparto de las corrientes de salida para funcionamiento en paralelo.

    - MTBF: Es el tiempo medio entre cada ocurrencia de una parada específica por fallo(o avería) de un proceso. La inversa de la frecuencia con que ocurre cada parada.

    - MTTR: Es el acronimo de la palabras inglesas Medium Time to Repair, o tiempo medio de reparado de avería.

- Que la estructura modular permite alcanzar algo grado de MTBF y bajos valores de MTTR.

- Tener en cuenta la distorsion armonica
- Perdida de potencia eléctrica por conmutación.


#### Opciones a tener en cuenta

- Funcionamiento en paralelo
- Comunicaciones RS-485 MODBUS / PROFIBUS
- By-Pass manual

    - SPWM: Consiste en comparar una señal de referencia (senoidal) con una señal portadora (triangular).

### Inversor onda modificada

- Estos inversores son economicos
- No entregan el tipo de señal  adecuada para el buen funcionamiento de electrodomesticos y equipos industriales.
- Entrega una señal con mucha distorsión armónica que deteriora la vida útil de electrodomesticos.
- La respuesta es baja debido a la alta distorsión armónica.
- Los armonicos distorsionan la forma de onda de salida, elevando la temperatura de los dispositivos semiconductores.
- Generan pérdidas de potencia en la conmutación.

- Repercusiones de usar estos inversores:
    - Las altas frecuencias de los armónicos en señales distorsionadas producen interferencias electromagnéticas que afectan negativamente el funcionamiento de los sistemas de telecomunicaciones.
    - En motores o equipos con bobinas se calientan.( Provoca calentamientos y daños en el aislamiento termico de sus arrollamientos).
    - Aumentan la impedancia de fuente
    - Produce perdidas debidas a las corrientes de Foucault.

- Usos:  demanda energetica reducida.
    - Televisores
    - Cargas de telefonos
    - Iluminación domestica


### Inversor onda pura

- Convierte corriente de precisa y alta calidad.
- Esta diseñado para abastecer todo tipo de aparatos electrónicos
- Adecuados para alimentar aparatos más exigentes como grandes electrodomésticos motorizados: lavadoras, refrigeradores y electronica considerada sensible como las bombas de agua.
- Algunos tienen una eficiencia mayor al suministrado por compañia aumentando la vida util de los aparatos electrónicos.
- Rango de 300 W hasta los 4000 W. Los más utilizados iguales o superiores a 1500W.


## Elección de inversor 

- Potencia: Lo recomendable es que el inversor trabaje al 70%, para evitar sobrecargas. 
    Ejemplo: Si el consumo es de 1300W es recomendable usar uno de 2000 que de 1500 para evitar riesgos.

