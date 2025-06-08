## Switch-Mode-Power-Supply-

This project involves the design and development of a Switched-Mode Power Supply (SMPS) that converts 240V AC input to a fixed 30V DC output, with high efficiency, compact size, and robust protection features.

##Project Goals

 Parameter               | Target Value(s)              | Notes                                |
|-------------------------|------------------------------|--------------------------------------|
| Output Voltage          | 30V                          | DC output                            |
| Output Current          | 10A                          | Continuous load current              |
| Peak Current Handling   | 12A – 15A                    | Short-term peak support              |
| Input Voltage           | 240V AC                      | Mains input                          |
| Ripple Voltage          | ≤ 50mV                       | At full load                         |
| Efficiency              | ≥ 90%                        | Target at rated load                 |
| Line Regulation         | ±0.5% – ±1%                  | Input voltage variation              |
| Load Regulation         | ±0.5% – ±2%                  | Load current variation               |
| Voltage Ramp            | 50ms – 500ms                 | Soft-start control                   |
| Response Time           | ≤ 1ms (goal ≤ 100µs)         | Transient response time              |
| Switching Frequency     | 50kHz – 500kHz               | Design-dependent                     |
| Over Voltage Protection | Trigger at 45V – 48V         | Protects load if voltage overshoots  |
| Over Current Protection | Limit at 14.4A – 18A         | Prevents overload                    |


This document outlines all critical targets for electrical, thermal, and safety performance. As the design evolves, simulation results and measured data will be compared to these values for validation.
