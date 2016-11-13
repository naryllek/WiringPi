set(gpio_srcs gpio.c readall.c pins.c)

add_library(GpioLib ${gpio_srcs})