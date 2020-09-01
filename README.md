# `rza1`

[Peripheral access API] for [the Renesas RZ/A1 MPU family] generated by [svd2rust]. The SVD file is being translated from the user manual by hand.

[Peripheral access API]: https://docs.rs/svd2rust/0.14.0/svd2rust/#peripheral-api
[the Renesas RZ/A1 MPU family]: https://www.renesas.com/us/en/products/microcontrollers-microprocessors/rz/rza/rza1h.html
[svd2rust]: https://github.com/rust-embedded/svd2rust

## Progress

The library is only updated passively and therefore there's no particular schedule on when these are going to be made available. If you would like to contribute to the project, please send a pull request!

 - [ ] Secondary Cache (L2C-310)
 - [ ] LSI Internal Bus
 - [x] **Clock Pulse Generator**
 - [ ] Interrupt Controller (PL390)
 - [x] **Interrupt Controller (Miscellaneous Registers)**
 - [ ] Bus State Contrller
 - [ ] Direct Memory Access Controller
 - [ ] Multi-Function Timer Pulse Unit 2
 - [x] **OS Timer**
 - [ ] Watchdog Timer
 - [ ] Realtime Clock
 - [x] **Serial Communication Interface with FIFO**
 - [ ] Serial Communications Interface
 - [ ] Renesas Serial Peripheral Interface
 - [ ] SPI Multi I/O Bus Controller
 - [ ] I²C Bus Interface
 - [ ] Serial Sound Interface
 - [ ] Media Local Bus
 - [ ] CAN Interface
 - [ ] IEBus Controller
 - [ ] Renesas SPDIF Interface
 - [ ] CD-ROM Decoder
 - [ ] LIN Interface
 - [ ] Ethernet Controller
 - [ ] A/D Converter
 - [ ] NAND Flash Memory Controller
 - [ ] USB2.0 Host/Function Module
 - [ ] Digital Video Decoder
 - [ ] Video Display Controller 5
    - [ ] Input Controller
    - [ ] Scaler
    - [ ] Image Quality Imprvoer
    - [ ] Image Synthesizer
    - [ ] Output Image Generator
    - [ ] Output Controller
    - [ ] System Controller
 - [x] ~~Dynamic Range Compression~~ *No public documentation available*
 - [ ] LVDS Output Interface
 - [x] ~~Image Renderer (IMR-LS2)~~ *NDA required*
 - [x] ~~Image Renderer for Display (IMR-LSD)~~ *NDA required*
 - [ ] Display Out Comparison Unit
 - [x] ~~Renesas Graphics Processor for OpenVG~~ *No public documentation available*
 - [ ] JPEG Codec Unit
 - [ ] Capture Engine Unit
 - [ ] Pixel Format Converter
 - [ ] SCUX
 - [ ] Sound Generator
 - [x] ~~SD Host Interface~~ *No public documentation available*
 - [ ] MMC Host Interface
 - [ ] Motor Control PWM Timer
 - [ ] On-Chip RAM
 - [x] **Ports**
 - [x] **Power-Down Modes**
 - [ ] Debugger Interface
 - [x] ~~EthernetAVB~~ *NDA required*

## License

This library is released under public domain. The library is provided "as is" without warranty of any kind - in no event shall the author be liable for any claim, damages or other liability arising out of or in connection with this library.

The SVD file includes some excerpts from the user manual for your convenience. Please refer to the official document for the latest, more detailed information.
