# Encoders
There are 3 methods, encoders, magnetic encoders and hall effect sensors.  Here's how you'd [wire them](https://docs.simplefoc.com/foc_shield_connect_hardware) to the SimpleFOC Shield. 

Encoders will have the 3-phase wires plus 5V and GND.  Magnetic encoders will be either SPI, I2C, or Analog, with the appropriate wires for each plus 5V and GND. Hall sensors have the 3-phase wires plus 5V and GND.

The [RioRand 350W 6-60V PWM DC Brushless Electric Motor Speed Controller](https://www.amazon.com/dp/B087M2378D?ref=ppx_yo2ov_dt_b_product_details&th=1) only supports a Hall sensor or regular encoder, not magnetic.


- [Magnetic sensor AS5048 a/b](https://www.youtube.com/watch?v=hhSib8TQQps&t=8s) Video.

- [Magnetic AS5600 Encoder](https://github.com/RobTillaart/AS5600) Arduino library

