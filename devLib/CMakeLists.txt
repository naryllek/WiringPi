
set(devLib_srcs     ds1302.c maxdetect.c  piNes.c
                    gertboard.c piFace.c
                    lcd128x64.c lcd.c
                    scrollPhat.c
                    piGlow.c)


set(devLib_hdrs     ds1302.h gertboard.h  lcd128x64.h  lcd.h  maxdetect.h piFace.h  piGlow.h  piNes.h
                    scrollPhat.h)


add_library(DevLibLib ${devLib_srcs})