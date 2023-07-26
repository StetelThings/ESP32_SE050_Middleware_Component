# SE050 component for ESP32-C3

Tested and working with *NXP Plug & Trust Middleware* version *4.3.1*.
Works with *ESP IDF 4*. Not compiling with version 5 of IDF.

## Component usage

- Copy the component inside the component folder of your project as *se050* folder.
- Download the *NXP Plug & Trust Middleware* and copy it into the *se050* component folder as *simw-top* subfolder.
- Edit i2c_esp32.h to change i2c pins definitions, if needed.
- Use the *i2c_esp32_set_status()* function to avoid the component to initialize the i2c port if it has been already initalized in advance.


