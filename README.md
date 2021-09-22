It is basically copy/paste espressif example, just adapted to use with PIO for arduino:
https://github.com/espressif/esp-idf/tree/master/examples/protocols/pppos_client


Some small changes in code are made as a part of excercise, to not deinit modem and netif and see how subscribe works. Also addition in code to wait when SIM is registered in network. Code tested with SIM800L, because BG96 seems to not register in my country for some reason.

To test code with BG96 or SIM7600 or other settings like UART pins can be changed in platformio.ini.

