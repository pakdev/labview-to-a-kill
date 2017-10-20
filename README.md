# LabVIEW To a Kill
A first person shooter (FPS) created entirely in LabVIEW using the 3D picture control. The objective of the game is to shoot 10 randomly placed targets as quickly as possible. Movement is accomplished by bouncing your leg(s) up and down and pressing the W, A, S, D keys. Leg motion is captured by a 2-axis ADXL213 accelerometer. This particular accelerometer generates a PWM signal that's read by a Sparkfun Redboard controlled by LINX. If enough rising edges are captured within a particular time frame, a "step" is registered and your player can advance. Additionally, all walls have collision detection logic and the 3D picture control functions have been abstracted into classes so switching between a control window/render window is seamless.

[Demo](https://www.youtube.com/watch?v=kU5iaaE5-PM)

_Note: This was my entry to an internal competition at NI._
