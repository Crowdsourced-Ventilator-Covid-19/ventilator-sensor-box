# ventilator-sensor-box
Sensor cluster that provides pressure/flow measurements, compatible with any ventilator design with an i2c port

This design has all the necessary sensory requiremens for a ventilator:
 - Inspiratory volumetric flow and temperature measurement
 - Expiratory volumetric flow and temperature measurement
 - Patient guage pressure measurement

All the sensors are muxed into a single I2c bus, and that I2c bus is connected with a i2c differential breakout, to allow placing the sensor box at the patient, which can be 4-5 feet from the ventilator.  The connectors utilize a standard ethernet CAT5 cable:

## BOM
| Count | Item | Cost |
| --- | --- | --- |
| 3 | [differential pressure sensor](https://ncd.io/differential-pressure-sensor-arduino/) | 3 x $60 |
| 1 | [i2c mux](https://learn.adafruit.com/adafruit-tca9548a-1-to-8-i2c-multiplexer-breakout) | $7 |
| 2 | [i2c differential breakout](https://www.sparkfun.com/products/14589) | 2 * 11 |
| 2 | venturi tubes | |
| 1 | 5-way Y | |

 
