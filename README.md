# ARM-Weight-Distance-Temperature-Meter
In this project, I implemented a multi-function system for Real-Time Monitoring purposes using ARM STM32F401 microcontrollers and sensors.

* ### Tempreture Sensing
  This subsystem uses a LM50 temperature sensor interfacing with ADC. It also includes an LCD screen to display the temperature.
<p align="center">
<img src="/Images/STM32-LM35-Temperature-Sensor.jpg" width="600" height="200" align="center">
</p>
<p align="center">
<img src="/Images/Temperature.jpg" width="600" height="400" align="center">
</p>


* ### Distance Sensing
  This rapid-response subsystem uses a GP2Y0A700K0F distance which is one thee most accurate infrared sensors with analog output. Also it uses usin timer input capture mode with interrupts and a LCD screen for monitoring.
<p align="center">
<img src="/Images/s-l400.jpg" width="300" height="150" align="center">
</p>
<p align="center">
<img src="/Images/distance.jpg" width="600" height="400" align="center">
</p>


* ### Weight Sensing
  The subsystems applys a load cell and AD623 (an integrated instrumentation amplifier that delivers rail-to-rail output swing using supply) interfacing with ADC.
<p align="center">
<img src="/Images/Load Cell.jpg" width="300" height="250" align="center">
</p>
<p align="center">
<img src="/Images/Weight.jpg" width="600" height="400" align="center">
</p>

