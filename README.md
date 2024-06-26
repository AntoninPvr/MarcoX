<h1 align="center">
    <img src="https://github.com/AntoninPvr/MarcoX/blob/main/img/logo.png?raw=true" alt="MarcoX Logo" width="200"></a>
    <br>
    MarcoX
</h1>

---
![Static Badge](https://img.shields.io/badge/status-active-green)
![GitHub Release](https://img.shields.io/github/v/release/AntoninPvr/MarcoX)
![GitHub License](https://img.shields.io/github/license/AntoninPvr/MarcoX)

<p float="left">
  <img src="https://github.com/AntoninPvr/MarcoX/blob/main/img/logo_orange_pi.png?raw=true"  width="100" style="margin-right: 30" />
  <img src="https://github.com/AntoninPvr/MarcoX/blob/main/img/logo_rfid.png?raw=true" width="50" style="margin-right: 30"/>
  <img src="https://bde-tps.fr/static/media/logo-bde.7108c70842e22deaef1d.jpg" width="80" />
</p>


MarcoX is the new version of the original Marco project based on Raspberry PI and old style resistive screen. This new version is based on Orange PI zero 2W with a 7" capacitive touch screen and aims to be more reliable and easier to replicate.

Software was also modernized and is available here : https://github.com/LOISGALLAUD/MARCONEO

Marco is a project that aims to create a payment terminal for a school BDE (French equivalent of Student Union). It is based on a RFID card system. The terminal is used by the students to pay for their meals or drinks. The terminal is connected to a self-hosted server that manages the accounts of the students. This terminal act as cash register.

This project is related to InsidePSBS app. Students can check their account and history on this mobile app available on IOS and Android. https://github.com/info-telecom-strasbourg/InsidePSBS (Reserved to TPS and ESBS students)

<p float="left">
  <img src="https://github.com/AntoninPvr/MarcoX/blob/main/img/render/full.JPG?raw=true"  width="46%"/>
  <img src="https://github.com/AntoninPvr/MarcoX/blob/main/img/render/frame_bellow.JPG?raw=true" width="50%" /> 
</p>

## Specifications

* **Screen**: 7" capacitive touch screen
* **RFID reader**: 125kHz compatible
* **Power supply**: USB-C 5V 3A
* **Battery**: Support power bank up to 20mm thickness
* **SBC**: Orange PI zero 2W
    * SoC: Allwinner H618 quad-core Cortex-A53 @ 1.5GHz
    * RAM: 1GB LPDDR4
    * Wi-Fi: 802.11 ac (Wi-Fi 5)
    * Bluetooth: 5.0
* **Dimensions**:
    * Length: 188mm
    * Width: 137mm
    * Height: 71mm
    * 1.8L volume

## Shopping list

### Electronic parts

* Orange PI zero 2W with 1GB RAM or more
* Micro SD card 16GB ore more, U3 speed class or more
* 7" Waveshare touch screen or compatible with HDMI input
* 125kHz RFID reader
* USB-C power supply
* mini HDMI to HDMI 100mm cable: A2 to C1
* USB-C to micro usb 100mm cable: W3R to T1B
* USB-C pannel 17mm center distance mount connector 200mm
* Power bank (optional)

    ---

### Mechanical parts
* M3 screws 16mm flat-head x4
* M3 screws 10mm x10
* M3 inserts x14
* 6mm plywood for the enclosure

    ---
### Parts details
| | |
|---|---|
| Orange PI zero 2W |<p align="right"> <img alt="Orange PI zero 2W" src="https://github.com/AntoninPvr/MarcoX/blob/main/img/orange_pi_zero_2w.jpg?raw=true" width="200">
|Mini HDMI to HDMI 100mm cable: (A2 to C1). Large side of HDMI is on ribbon cable side. Mini HDMI large side is on ribbon connector side.  | <p align="right"><img alt="HDMI to Micro HDMI adapter" src="https://github.com/AntoninPvr/MarcoX/blob/main/img/hdmi_to_micro_hdmi.jpg?raw=true" width="200"></p>|
|USB-C to micro usb 100mm cable: W3R to T1B|<p align="right"><img alt="HDMI to Micro HDMI adapter" src="https://github.com/AntoninPvr/MarcoX/blob/main/img/usbc_to_micro_usb.jpg?raw=true" width="200"></p>|
|USB-C pannel 17mm center distance mount connector 200mm|<p align="right"><img alt="HDMI to Micro HDMI adapter" src="https://github.com/AntoninPvr/MarcoX/blob/main/img/usbc_pannel_mount.jpg?raw=true" width="200"></p>|
| Power bank 10000mAh (optional) |<p align="right"><img alt="Power bank" src="https://github.com/AntoninPvr/MarcoX/blob/main/img/power_bank.jpg?raw=true" width="200"></p>|

### Screen

Screen is 7" Waveshare touch screen or compatible with HDMI input it can be a compatible one as long as it has the same connectors and the same size.

<p align="center">
    <img alt="Screen front" src="https://github.com/AntoninPvr/MarcoX/blob/main/img/screen_front.jpg?raw=true" width="45%">
&nbsp;
    <img alt="Screen BAck" src="https://github.com/AntoninPvr/MarcoX/blob/main/img/screen_back.jpg?raw=true" width="45%">
</p>

## 3D printed parts

All parts are in `.stl` format. They are designed to be printed without support.

### Printer settings

Tested settings, but feel free to adapt them to your printer and material.:

* Layer height: 0.2mm
* Infill: 20%
* Nozzle diameter: 0.4mm
* Material: PLA or PETG

<p align="center">
    <img alt="screen frame" src="https://github.com/AntoninPvr/MarcoX/blob/main/img/render/screen_frame.JPG?raw=true" width="30%">
&nbsp;
    <img alt="Internal frame" src="https://github.com/AntoninPvr/MarcoX/blob/main/img/render/internal_frame.JPG?raw=true" width="30%">
&nbsp;
    <img alt="Card reader" src="https://github.com/AntoninPvr/MarcoX/blob/main/img/render/card_reader.JPG?raw=true" width="33.6%">
</p>

* ### Screen frame

    **File:** [screen_frame.STL](https://github.com/AntoninPvr/MarcoX/blob/main/screen_frame.STL)

    This frame allow screen and top cover to be attached without overthickness and to secure enclosure and removable top cover.

* ### Internal frame

    **File:** [internal_frame.STL](https://github.com/AntoninPvr/MarcoX/blob/main/internal_frame.STL)

    This frame is attached to the screen and is used to fix all other parts.

    *Note: For this part adding support may improve print quality*

* ### Card reader mount

    **File:** [card_reader.STL](https://github.com/AntoninPvr/MarcoX/blob/main/card_reader.STL)

    This mount is used to fix the RFID reader to the enclosure as close as possible to improve card detection.

* ### Antenna support

    **File:** [antenna_support.STL](https://github.com/AntoninPvr/MarcoX/blob/main/antenna_support.STL)

    This part is used to fix the WiFi antenna and improve signal quality.

## Enclosure 

<p align="center">
    <img src="https://github.com/AntoninPvr/MarcoX/blob/main/img/render/enclosure.JPG?raw=true"  width="48%"/>
</p>

This is basically a wooden box with finger joints. It is composed of 5 parts: 1 base, 2 long sides and 2 short sides.

### Laser cut parts
Laser cut parts are in `.svg` format. Red lines width is 0.2mm and are adapted for [Trotec Speedy 100](https://www.troteclaser.com/static/pdf/speedy-100/Fiche-technique-Speedy-100C-8063-fr.pdf) laser cutter.
Material: 6mm plywood recommended.

<p align="center">
    <img src="https://github.com/AntoninPvr/MarcoX/blob/main/laser/thickness_6mm/top_cover.svg?raw=true"  width="48%"/>
    <img src="https://github.com/AntoninPvr/MarcoX/blob/main/laser/thickness_6mm/base.svg?raw=true" width="48%" /> 
</p>

<p align="center">
    <img src="https://github.com/AntoninPvr/MarcoX/blob/main/laser/thickness_6mm/long_side.svg?raw=true"  width="36%"/>
    <img src="https://github.com/AntoninPvr/MarcoX/blob/main/laser/thickness_6mm/long_side_usb-c.svg?raw=true" width="36%" /> 
    <img src="https://github.com/AntoninPvr/MarcoX/blob/main/laser/thickness_6mm/short_side.svg?raw=true" width="26.3%" />
</p>

## Related projects

* #### Software associated with MarcoX is available here :
    > https://github.com/LOISGALLAUD/MARCONEO

    <p align="left">
        <img alt="Main screen" src="https://github.com/LOISGALLAUD/MARCONEO/blob/master/data/images/readme/main_menu.png?raw=true" width="30%">
    &nbsp;
        <img alt="MarcoNeo custom" src="https://github.com/LOISGALLAUD/MARCONEO/blob/master/data/images/readme/pricemodifier.png?raw=true" width="30%">
    &nbsp;
        <img alt="MarcoNeo history" src="https://github.com/LOISGALLAUD/MARCONEO/blob/master/data/images/readme/historique_menu.png?raw=true" width="30%">
    </p>

---

* #### Mobile App InsidePSBS source is available here :
    > https://github.com/info-telecom-strasbourg/InsidePSBS
    
<p align="center">
    <a href="https://app.its-tps.fr" target="_blank">
        <img src="https://app.its-tps.fr/logo.png" width="20%"/>
    </a>
 </p>

 ---

* #### Old version of Marco "MarcoSlim" project is available here :
    > https://github.com/AntoninPvr/MarcoSlim

    <p align="left">
        <img alt="MarcoSlimFront" src="https://github.com/AntoninPvr/MarcoSlim/blob/main/img/render/full.JPG?raw=true" width="30%">
    &nbsp;
        <img alt="Screen BAck" src="https://github.com/AntoninPvr/MarcoSlim/blob/main/img/render/internal.JPG?raw=true" width="30%">
    </p>
