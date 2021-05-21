# atmega_rtc

Simple Arduino code to use a 32768 crystal and Timer2 on Atmega processors, to maintain an RTC during sleep mode.

Two examples are presented for timekeeping: one maintains an ASCII string HH:MM:SS, the other maintains BCD encoded time in six sequential bytes, H,H,M,M,S,S
