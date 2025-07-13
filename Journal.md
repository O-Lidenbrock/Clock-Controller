## 7_9_2025

30m Begin!
  I have a clock motor laying around (for an analog mounted wall clock). The ideas is hacking it to do whatever I want. Mode 1 is regular clock. Then, if you press start, it runs like a watch chronometer.


## 7_12_2025 

45m Sketch the schematic
  Motor controllers are weird. The wiring diagram I'm going off had several extra traces I don't need (they're for an extra switch he was using). Once I figured that out, I read some articles about H-bridges to figure out the motor controller and drew the traces.

  The switches are a one-row matrix to save space.

30m KiCad the schematic
  I planned to use a Xiao ESP32-C3, but the documentation says "ESP32-C3 is unable to operate without an external main crystal clock." As much as I'd love to wire a SMD crystal oscillator, I want this working more. ESP