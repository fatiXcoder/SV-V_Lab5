| Op-Id | Operation                        | Purpose                                                                                                |
| ----- | -------------------------------- | ------------------------------------------------------------------------------------------------------ |
| OP-01 | Initialize Chamber               | Initialize the conservation chamber when the system is powered on.                                     |
| OP-02 | Perform Sensor Self-Check        | Verify that all essential sensors are working correctly.                                               |
| OP-03 | Check Control Devices            | Verify that environmental-control devices are operational.                                             |
| OP-04 | Register Artifact                | Record the identification information of the artifact placed inside.                                   |
| OP-05 | Load Environmental Profile       | Load the required environmental limits for the artifact.                                               |
| OP-06 | Monitor Door Status              | Continuously check whether the chamber door is open or closed.                                         |
| OP-07 | Monitor Environmental Conditions | Monitor the temperature and humidity of the chamber.                                                   |
| OP-08 | Adjust Temperature               | Attempt to restore temperature when it moves outside the permitted range.                              |
| OP-09 | Adjust Humidity                  | Attempt to restore humidity when it moves outside the permitted range.                                 |
| OP-10 | Verify Environmental Recovery    | Confirm through sensor readings that the environment has returned to permitted limits.                 |
| OP-11 | Activate Protection Controls     | Activate additional controls when environmental conditions cannot be corrected.                        |
| OP-12 | Generate Operator Alert          | Notify the museum operator about abnormal or dangerous conditions.                                     |
| OP-13 | Detect and Respond to Vibration  | Detect significant vibration and suspend activities that could risk the artifact.                      |
| OP-14 | Switch to Emergency Power        | Switch to an emergency power source when normal power is lost.                                         |
| OP-15 | Authorize Artifact Removal       | Allow artifact removal only after confirming the chamber is safe and no protection response is active. |
