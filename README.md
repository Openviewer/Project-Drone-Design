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
