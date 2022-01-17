# lv_port_mps3_an547_cm55
A LVGL port for Cortex-M55 running on an [Arm official FPGA prototype development board](https://developer.arm.com/tools-and-software/development-boards/fpga-prototyping-boards/mps3) called MPS3 ([AN547](https://developer.arm.com/tools-and-software/development-boards/fpga-prototyping-boards/download-fpga-images#)), see **Figure 1**. It is also possible to run the project template on a free emulator called **Fixed-Virtual-Platforms**, [Corstone-300-FVP](https://developer.arm.com/tools-and-software/open-source-software/arm-platforms-software/arm-ecosystem-fvps).



**Figure 1 Arm MPS3 FPGA prototyping board** 

![](https://developer.arm.com/-/media/Arm%20Developer%20Community/Images/Development%20Boards/Arm_MPS3_prototyping_system.png?revision=79a108aa-abe8-4a21-b453-ad6c2d6e82b2&h=409&w=400&hash=F7DEA4E2D2C854ECAC5BBCC8804D6107) 



## Features

- LVGL 8.1.x  (CMSIS-Pack)
- 320 * 240 RGB565 LCD Display connected with an Integrated Color LCD parallel interface. 
- Default System Clock: 32MHz (50MHz Max)
- CPU: Cortex-M55 with Helium
  - DCache
  - ICache
  - ITCM: 512KB
  - DTCM: 512KB
- NPU: Ethos-U55
- PRAM (Used for Code and RO-Data): 2MByte
- SRAM: 4MByte
- DDR4: 1GByte



## License

- LVGL used in this project is under MIT license.
- This project template is under Apache 2.0 license.



## Reference

1. [Arm Corstone SSE-300 with Cortex-M55 and Ethos-U55 Example Subsystem for MPS3](https://developer.arm.com/documentation/dai0547/c?_ga=2.157798205.688811587.1624957483-616249991.1623083451)



