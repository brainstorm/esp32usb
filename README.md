ESPUSB port for the ESP32 (WIP, NOT WORKING YET)
================================================

This is an attempt to incrementally port the [espusb codebase](https://github.com/cnlohr/espusb) to the esp32 via esp-idf-template. To get started just clone and:

```bash
cmake . && make -j8
```

At the moment of writing this it's purely exploratory, don't expect it to compile nor work at all... for now. Current status:

```bash
/Users/romanvg/tmp/esp32usb/main/usb_asm_1bit.S: Assembler messages:
/Users/romanvg/tmp/esp32usb/main/usb_asm_1bit.S:253: Fatal error: cannot find suitable trampoline
```
