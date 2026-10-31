# Macintosh SE FDHD repair
February 2026

<img src = "images/mac_working.jpg" alt = "alt" width="400">

## Initial condition
Fan spins but no startup chime, display or drive activity. 5V and 12V rails are present at floppy connector.
## CRT
Upon disassembly, it was noticed that the glass was broken at the neckboard. The CRT was replaced.

<img src = "images/mac_brokencrt.jpg" alt = "alt" width="400">

## Analog board
There was still no display activity with the new CRT. The high voltage was also missing. The pad of C9 (1000uF 16V) showed some corrosion. The capacitor was leaking and was replaced.

<img src = "images/mac_leakycap.jpg" alt = "alt" width="400">

The unit now showed diagonal lines. Many causes were explored, but the real cause was the lack of video signal coming from the logic board. The diagonal lines were simply due to a wrong cutoff setting.

<img src = "images/mac_diagonal.jpg" alt = "alt" width="400">

## Digital board
There was significant corrosion around the axial electrolytics. All caps were desoldered, the board was cleaned in IPA, and new caps were installed. The sockets were also cleaned, and the battery was replaced.

<img src = "images/mac_logiccleaning.jpg" alt = "alt" width="400">

The lack of video signal was caused by some cold solder joints around the video connector. All joint were reflowed, and the display presented a diagnostic screen. The error code indicated a memory error.

<img src = "images/mac_ramerror.jpg" alt = "alt" width="400">

Cleaning the RAM slots had no effect. New memory was purchased, and the flashing floppy appeared with mouse cursor.

<img src = "images/mac_floppy.jpg" alt = "alt" width="400">

## PSU
The power supply was recapped. All capacitors were within tolerance.
## BlueSCSI
With the unit working and adjusted, a BlueSCSI emulator was used as a boot medium with System 6.0.8.
