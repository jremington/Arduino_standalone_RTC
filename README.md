# atmega_rtc

Simple standalone Arduino code to use a 32768 crystal and Timer2 on Atmega processors, to maintain time during sleep mode.  Fuses must be set so that the main processor is clocked using the internal RC oscillators (usually 8 MHz).

Two examples are presented for timekeeping: one maintains an ASCII string HH:MM:SS, the other maintains BCD encoded time in six sequential bytes, H,H,M,M,S,S
