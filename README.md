# Project-Drone-Design
This is a simple 3D model design for a Drone based on the information from Coursera course ***3D Model Creation with Autodesk Fusion 360***
## Design Critria
### Component Selection
- **Motor Specifications**
  - Motor Specs DYS MR2205-2759KV
    - Diameter - 22mm
    - Height - 05mm
    - KV - revolutions per 1 volt (e.g. *11.1v x 2750 = 30525 rpm*)
    - Trust - based on battery and prop
    - Amperage draw - increases with throttle/rpm
    - Ideal prop - based on battery and weight
  
- **Battery Specifications**
  - Battery ratings Turnigy Lipo 3s 1500 mAh 20-30C
    - Number of cells (S) 3.7V/cell
      - 3S  = 11.1v
      - 4S = 14.8v
    - Amp Hour (aHr)
      - 1500mA for 1hr
    - Discharge (C)
      - 20C = 20 * 1.5a = 30amp continuous supply
      - 30C = 30 * 1.5a = 45amp supply for 10sec
      
- **Multirotor basics**
  - Signal received by RX module
  - Signal sent to Flight Controller
  - Flight Controller converts input to motor output
  - Signal sent to ESC and Motors

- **Multirotor add-ons**
  - PDB or ESC with BEC
  - Camera and TX module
  - Servo or Brushless Gimbal
  - Additional cameras or sensors
  
 ### Camera System parts

- **Camera**
    - FatShark 700TVL CMOS camera NTSC/PAL
    - Light weight
    - Low power consumption
    - Inexpensive
- **Video transmit**
    - SkyZone TS5823 5.8GHz 32ch A/V 200mW
    - Small/light
    - 1 mile range
    - 32 channels
    - GoPro compatible
- **Monitor and receiver**
    - 7in 1024x600 32ch 5.8GHz LCD monitor Fieldview 777
    - High resolution
    - 32 channel
    - 2.4GHz protected
    - Built in battery
    - Audio
