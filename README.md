# wiegand_esphome_module
custom wiegand component for esphome.

This module allow to connect weigand sensors with esphome.
Its my first module so maybe you find any bad practice in de code.

Copy wiegand_device.h in the root of esphome (bad practice I know that should be treated like a custom component).
Use the .yalm to inspire yours.

how to add the module?
1. Create a empty project with esphome named door_reader.
2. comment the line with the #include wiegand_device.h in the yalm
3. Compile
4. Create wiegand_device.H in the following path
    /config/esphome/door_reader/src/wiegand_device.h and update de variables topic and doorID.
5. uncomment the line with the #include wiegand_device.h in the yalm
6. Compile again.
