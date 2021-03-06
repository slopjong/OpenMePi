OpenMePi
======

OpenMePi is an alarm and access control system based on the Raspberry Pi board. It will replace [OpenDuino](http://wiki.hackerspace.lu/wiki/OpenDuino) in order to get a maintainable and reliable system which is easy to extend at the same time.

OpenDuino has become hard to maintain and especially the design of the state machine lacks of understandability. No documentation is available which makes life hard for people that join that project.

As of now a state machine and a modular hardware architecture have been carefully designed which allow to develop and test the modules indepentenly.

Hardware Architecture
----------------

In the OpenMePi system the peripherals are connected to the i2c bus instead of direct GPIO connections. This allows to make sensors and actuators more intelligent and doing stuff within their own control flow.

![models/HardwareConfiguration/hardware_configuration.png](models/HardwareConfiguration/hardware_configuration.png)
