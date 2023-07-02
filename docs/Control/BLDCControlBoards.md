# BLDC Control Boards
In general there are two formats for these control boards.  Ones that have an onboard Arduino based controller usually the STM32G473CE with an FPU, and those that keep the microcontroller separate.  The later is the approach taken by the *SimpleFOCProject*.

See the video tutorials on [Programming the STM32](https://www.youtube.com/watch?v=hYYRfhhvTYo&list=PLr0mEvO7yBe6Ga7wJpRTZpxAYSvgWY0A-&index=1&ab_channel=TerminalTwo).

General Info on FOC controllers:

- Can use hall effect sensors or back EMF to determine the position of the rotor. 

- FOC is a sensorless method that reads the trapezoidal-shaped feedback voltages from the motor stator windings and then processes that feedback into control signals for the motor. The motor stator windings are driven by three MOSFET half-bridges.

## Components

3-Phase gate drivers:

- The MP6540 and MP6540A are 3-phase, brushless DC motor drivers that integrate three half-bridges consisting of six N-channel power MOSFETs, pre-drivers, gate drive power supplies, and current sense amplifiers. The MP6540 has enable and PWM inputs for each half-bridge. The MP6540A has separate high-side and low-side inputs; otherwise, both parts are identical.

- L6234 driver

- DRV8300 series

- [RioRand 350W 6-60V PWM DC Brushless Electric Motor Speed Controller with Hall](https://www.amazon.com/dp/B087M2378D?ref=ppx_yo2ov_dt_b_product_details&th=1). See listing for instructions on how to use this.

## ODrive

- [Schematics](https://github.com/odriverobotics/ODriveHardware/tree/master/v3/v3.5docs)

## Tinymovr

- [Tinymovr Site](https://tinymovr.com/en-us)

- [Github](https://github.com/tinymovr/Tinymovr)

## SimpleFOC

The [SimpleFOC Project](https://simplefoc.com/) is software which can be used with multiple controllers, encoders, and motors.  The idea is 

- [MiniFOC Board](https://github.com/simplefoc/SimpleFOCMini) - Github



Here's a list of [supported hardware](https://docs.simplefoc.com/supported_hardware)


Gimbal controller board

- [HMBGC V2.2 board](https://docs.simplefoc.com/hmbgc) 
- AMT 103 CUI Encoder 2048ppr
- BLDC Gimbal Motor

- [SimpleFOC BLDC controller board](https://www.aliexpress.us/item/3256802309960476.html?spm=a2g0o.cart.0.0.7d1d38daLeI5N0&mp=1&gatewayAdapt=glo2usa&_randl_shipto=US)

- [Mini SimpleFOC controller board](https://www.aliexpress.us/item/3256804888906189.html?spm=a2g0o.cart.0.0.7d1d38daLeI5N0&mp=1&gatewayAdapt=glo2usa&_randl_shipto=US)

- [DRV8302 Motor Drive Module DC 5.5-45V 15A High Power BLDC Brushless PMSM Drive ST FOC Vector Control Amplifier Module](https://www.aliexpress.com/i/2255799940116021.html?gatewayAdapt=4itemAdapt) $40

- [USA-DIGITAL E3-8192 Encoder 8192ppr](https://www.usdigital.com/products/encoders/incremental/kit/E3)

## Open Source FOC Boards by Individuals
There are several boards that have been designed and published by individual makers.  These will be useful for building my own boards at a reasonable price.

### Mosquito Board

- [Mosquito Board Design Forum](https://community.simplefoc.com/t/mosquito-board-new-design/1621/12).  Tried this with PCLPCB but the hole size was not supported.  Also seems that the STM32 controller doesn't have a lot of memory.

- [User Guide](https://drive.google.com/file/d/1Ev1wcCPXnmiUsTl4JunoNijvsclqJlB7/view?pli=1)

- [Schematic](https://oshwlab.com/cost.co/20220126_bldc_mosquito_copy)

### Smart FOC Controller

- [Smart FOC Controller](https://oshwlab.com/xterminhate/focv1)

### Maakbaas

- [BLDC Board Design](https://maakbaas.com/diy-field-oriented-control-esc/logs/bldc-introduction/).  No manafactural design yet.  


### Electronoobs

- [My open source Arduino ESC - BEMF zero-cross](https://www.youtube.com/watch?v=VdkloigaxZo&ab_channel=Electronoobs)

- [Open Source ESC based on Arduino - High Speeds](https://www.youtube.com/watch?v=-ymTE-Nivzw&ab_channel=Electronoobs)

- [FOC Driver Controller PCB - Slow Brushless Control](https://www.youtube.com/watch?v=zSdetJsSeNw&list=TLPQMTQwNDIwMjNItSUN2eXk9Q&index=2&ab_channel=Electronoobs)

- [DRV8316 Driver board](https://campaign.aliexpress.com/wow/gcp/tesla-pc-new/index?UTABTest=aliabtest377151_530968&src=google&src=google&albch=shopping&acnt=708-803-3821&slnk=&plac=&mtctp=&albbt=Google_7_shopping&albagn=888888&isSmbAutoCall=false&needSmbHouyi=false&albcp=19131229154&albag=&trgt=&crea=en3256804888906189&netw=x&device=c&albpg=&albpd=en3256804888906189&gclid=Cj0KCQjwlumhBhClARIsABO6p-w3bRf7EMZsxSLopl-cxygHNJhkihahVgP2K2Dn7CQpQ4i913E1OWQaAsfLEALw_wcB&gclsrc=aw.ds&aff_fcid=d1ffcc3bc93647aa8b219269254a642c-1681589322040-00147-UneMJZVf&aff_fsk=UneMJZVf&aff_platform=aaf&sk=UneMJZVf&aff_trace_key=d1ffcc3bc93647aa8b219269254a642c-1681589322040-00147-UneMJZVf&terminal_id=732774282c91414d8bffe0f57a5cd880&wh_weex=true&wx_navbar_hidden=true&wx_navbar_transparent=true&ignoreNavigationBar=true&wx_statusbar_hidden=true&bt_src=ppc_direct_lp&scenario=pcBridgePPC&productId=3256804888906189&OLP=1085100208_f_group2&o_s_id=1085100208)

## References

- [Open Source Projects Website](https://oshwlab.com/)