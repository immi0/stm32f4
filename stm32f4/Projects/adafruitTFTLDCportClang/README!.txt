you need the STM32F4 library and source in ../../
you need the arm-none-eabi-gcc compiler

to compile type:
make

to flash type:
make flash

this will flash the programm using gdbserver/st-link
type c to continue the programm
/dev/ttyACM0 can be used by any terminal programm


sudo dfu-util  --device 0483:df11 --alt 0 --dfuse-address 0x08000000 --download TFTLCD_test_FSMC.bin