
## Change Log
| Version | Changes                                                                                                    |
| ------- | ---------------------------------------------------------------------------------------------------------- |
| 1.0.6   | * include build tools in dependencies so GitHub branch installs can run prepare/build reliably            |
| 1.0.5   | * restore platform alias to NessD16x so existing Homebridge config maps correctly                          |
| 1.0.4   | * make GitHub branch installs more compatible by removing lint from prepare script                         |
| 1.0.3   | * rename package to homebridge-ness-d16x-cg</br>* rename platform alias to NessD16xCG for side-by-side install clarity |
| 1.0.2   | * append " (Garage)" to labels of outputs configured as Garage Door for easier HomeKit differentiation |
| 1.0.1   | * add per-output Garage Door checkbox in config UI</br>* map selected outputs to HomeKit Garage Door service |
| 1.0.0   | * remove Night mode (not supported by Ness)</br>* rework state management sync between Ness and Homebridge |
| 0.0.8   | * rework interface connection logic with heartbeat and error support                                       |
| 0.0.7   | * add retry logic on interface connection errors                                                           |
| 0.0.6   | * add ability to control AuxiliaryOutputs                                                                  |
| 0.0.5   | * add verbose logging                                                                                      |
| 0.0.4   | * add support for Outputs and AuxiliaryOutputs</br>* add low battery alarm state                           |