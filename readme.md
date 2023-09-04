` Documentation is in progress! `

# OpenKNX KNeoPix

![KNEOPIX](Documentation/Renderings/rendered_case_assemble_Step_0.png)

## Preliminary Information about OpenKNX KNeoPix

OpenKNX KNeoPix is an innovative hardware solution designed specifically for DIY (Do It Yourself) projects. It has been developed to provide enthusiasts and hobbyists with the opportunity to implement creative solutions in the field of building automation and intelligent networking. It's important to note that KNeoPix does not come with any warranties. This DIY orientation means that users take full responsibility for assembly, configuration, and operation. It's worth noting that KNeoPix is fully compatible with the openKNX software, ensuring seamless integration and operation within the openKNX ecosystem.

### Hardware

KNeoPix's hardware is based on either the [XIAO RP2040](https://www.seeedstudio.com/XIAO-RP2040-v1-0-p-5026.html) or the [XIAO SAMD21](https://www.seeedstudio.com/Seeeduino-XIAO-Arduino-Microcontroller-SAMD21-Cortex-M0+-p-4426.html) microcontroller, in conjunction with the [openKNX BCU](https://github.com/OpenKNX/OpenKNX/wiki/NanoBCU) platform. This platform enables a wide range of applications in the field of building automation and intelligent networking.

### Power Supply

One of KNeoPix's standout features is its versatile power supply options. The hardware can be powered either directly via KNX bus voltage at 3.3V or 5V, allowing seamless integration into KNX-based building systems. Alternatively, KNeoPix can also be powered through an external voltage source ranging from 6V to 24V. This flexibility opens up a wide range of deployment possibilities and allows users to adapt KNeoPix to different requirements.

### Galvanic Isolation

Notably, when using an external voltage source, KNeoPix offers galvanic isolation from the KNX bus. This ensures a secure and reliable integration into KNX networks, protecting against potential electrical disturbances.

### Inputs and Outputs (IOs)

The availability of a total of 6 direct and 2 isolated inputs and outputs (IOs) offers a wide range of application possibilities. KNeoPix's primary function is to control RGB LEDs via the 2 isolated IOs, enabling the creation of captivating lighting effects in buildings. Additionally, the 6 direct IOs can be used for additional control tasks, making KNeoPix an incredibly versatile tool in building automation.

### Voltage Options

The ability to operate both the external voltage at 3.3V/5V as a direct power supply and at 6V to 24V as a variable power supply provides maximum flexibility in configuring and using KNeoPix. This allows users to tailor the hardware to specific requirements and seamlessly integrate it into existing systems.

### Pin Compatibility

Moreover, KNeoPix is pin-compatible with other XIAO series microcontrollers, such as the [XIAO ESP32C3](https://www.seeedstudio.com/Seeed-XIAO-ESP32C3-p-5431.html) or [XIAO ESP32S3](https://www.seeedstudio.com/XIAO-ESP32S3-p-5627.html). This compatibility further extends its versatility and allows users to leverage existing hardware and resources for their projects.

KNeoPix is thus a powerful, flexible, and highly customizable solution for building automation and intelligent networking, built on a solid hardware foundation and innovative technology. 

With its diverse range of applications, KNeoPix is the ideal choice for DIY projects that require creativity and self-reliance.
