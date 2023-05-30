Supports heating and cooling logic for zone based climate control systems. Create as many zones as needed and link to your own control panels via smart home system. 

Note that scheduling is intentionally not part of the climate nodes.

### Features

- Decides when to heat or cool based on current & target temperatures
- Multiple ways to configure e.g. heating only, cooling only, both heat & cool or manual control.
- Override current program with "away" & "boost" presets.
- Integration with MQTT and/or homeassistant.
- Safety cut out when temperature readings are stale (when setpoint is active).
- Configure minimum cycle time to protect equipment from rapid changes of state.
- Manual control for simpler use cases e.g. hot water timers that do not need a setpoint but require keep alive or boost functionality.
- Optional node status output to aid with debugging or deeper integration.

<i>Disclaimer</i>. Please note that these nodes are virtual and you alone are responsible for ensuring the safety of any equipment you connect.

Based on: https://github.com/thingzi/thingzi-logic-climate
