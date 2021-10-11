jwm_kicad_footprints_misc.pretty
================================

This is a collection of miscellaneous footprints for [KiCad](https://kicad-pcb.org). Currently, this is my only custom footprints library, but it's also a holding library before I can break footprints out into separate specialized libraries.

(You might also be interested in my related [misc symbols library](https://github.com/joem/jwm_kicad_symbols_misc) and [misc 3D models library](https://github.com/joem/jwm_kicad_3dmodels_misc.3dshapes) for KiCad.)

Footprints included in this library:

Footprint                                                 | 3D?   | Description
---------                                                 | :---: | -----------
Arduino_Nano_WithMFHeadersAnd3DModel                          | O | the KiCad library footprint with a found 3D model associated
C_Disc_D5.0mm_W2.5mm_P2.50mm_LZX                              | K | a small capacitor footprint made to look how they do on LZX Cadet PCBs
D_P7.62mm_Horizontal_LZX                                      | K | a diode footprint made to look how they do on LZX Cadet PCBs
ESP32_Devkit_V1_DOIT_JWM                                      | O | modified version of a found ESP32 devkit footprint
ESP32_Devkit_V1_DOIT_JWM_LessSilk                             | O | modified version of a found ESP32 devkit footprint, with less silkscreen
IDC-Header_2x05_P2.54mm_Vertical_EurorackPower                | K | a 2x5 IDC header with Eurorack power annotations
IDC-Header_2x08_P2.54mm_Vertical_EurorackPower                | K | a 2x8 IDC header with Eurorack power annotations
Jack_3.5mm_CUI_SJ1-3535NG_Horizontal_With3DModel              | O | the KiCad library footprint with a found 3D model associated
Jack_3.5mm_QingPu_WQP-PJ302M_Horizontal                       | C | a PJ302M jack with slot holes
Jack_3.5mm_QingPu_WQP-PJ302M_Horizontal_CircularHoles         | C | a PJ302M jack with round holes
Jack_3.5mm_QingPu_WQP-PJ398SM_Vertical_CircularHoles_With3DModel | O | the KiCad library footprint with a found 3D model associated
PinHeader_2x05_P2.54mm_Vertical_EurorackPower                 | K | a 2x5 pin header with Eurorack power annotations
PinHeader_2x08_P2.54mm_Vertical_EurorackPower                 | K | a 2x8 pin header with Eurorack power annotations
PinSocket_1x04_P2.54mm_Vertical_NoSilk                        | K | a 1x4 pin socket without any silkscreen
PinSocket_1x06_P2.54mm_Vertical_NoSilk                        | K | a 1x6 pin socket without any silkscreen
PinSocket_1x09_P2.54mm_Vertical_NoSilk                        | K | a 1x9 pin socket without any silkscreen
PinSocket_1x15_P2.54mm_Vertical_NoSilk                        | K | a 1x15 pin socket without any silkscreen
Potentiometer_Alpha_RD901F-20_Single_Horizontal_CircularHoles |   | a horizontally mounted Alpha potentiometer
Potentiometer_Alpha_RD901F-40-00D_Single_Vertical_With3DModel | O | the KiCad library footprint with a found 3D model associated
RCA-Phono_CUI-Devices_RCJ-01X_Horizontal                      |   | a horizontally mounted RCA phone connector
RCA-Phono_CUI-Devices_RCJ-02X_Vertical                        | C | a vertically mounted RCA phono connector (now with pin 1 as tip)
RCA-Phono_CUI-Devices_RCJ-02X_Vertical_InvertedPinNumbers     | C | same as RCA-Phono_CUI-Devices_RCJ-02X_Vertical but pin 2 is tip
R_Axial_P7.62mm_Horizontal_LZX                                | K | a small resistor footprint made to look how they do on LZX Cadet PCBs
Switch_Toggle_Mountain-Switch_10TF230_Horizontal              |   | a horizontally mounted SPDT toggle switch
misc_reference_for_test_and_whatever                          |   | three holes, not sure why I made this

3D? Column Key:

- `K` means it uses a model from the KiCad library
- `C` means it uses a model found in [my misc 3D models library](https://github.com/joem/jwm_kicad_3dmodels_misc.3dshapes)
- `O` means it uses a model made by someone else that isn't part of the KiCad library (no preview included for these)

For an easy preview of what these footprints look like, look in the [images](images/) folder.

Please feel free to use these footprints as you'd like in your own projects. If they help you, I'm glad.

