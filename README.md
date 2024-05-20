# Factory IO Assembler controlled by PLC FX3U
## Introduction
- This is a product assembler, with its functionality is to assemble the lid and the base in order to become a fished product.
- The number of completed products is kept track by a 7-segment display located next to the assembler.
- Emergency stop button for immediate stop and safety.
## How to run
- Add the .factoryio to "My scene" folder, which is usually located at "C:\Users\...\Documents\Factory IO\My Scenes". If you wish to make your own assembler model, you can set up like the provided schematic.
- Open the scene in Factory IO.
- Run the GX Works2 project and MX OPC Configurator at the same time.
- Connect the sensors and the actuators in driver tab in Factory IO same as the provided image so that the assembler can work properly.
- In the configuration tab, select OPC client DA/UA, with OPC server is Mitsubishi.MXOPC.6 so that GX Works can be connected to Factory IO.
- Run the simulation and see the result!
## Reference
- GX Works2: https://www.mitsubishielectric.com/fa/products/cnt/plceng/smerit/gx_works2/index.html
- MX OPC Configurator: https://emea.mitsubishielectric.com/fa/products/cnt/plc/plceng/other_eng/mx-opc
- Factory IO: https://factoryio.com/
