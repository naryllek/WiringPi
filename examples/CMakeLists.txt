set(wiring_pi_example_srcs          blink.c blink8.c blink12.c
                                    blink12drcs.c
                                    pwm.c
                                    speed.c wfi.c isr.c isr-osc.c
                                    lcd.c lcd-adafruit.c clock.c
                                    nes.c
                                    softPwm.c softTone.c
                                    delayTest.c serialRead.c serialTest.c okLed.c ds1302.c
                                    lowPower.c
                                    max31855.c
                                    rht03.c)
#add_executable(serialTest serialTest.c)
#target_link_libraries(serialTest WiringPiLib GpioLib DevLibLib)
