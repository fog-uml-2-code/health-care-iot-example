# Health Care IoT Example

This is the UML model for an example Body Area Network (BAN) IoT application, which serves as a case study for [FogUML2Code](https://github.com/fog-uml-2-code/fog-uml-2-code).

## Disclaimer
We would like to note that we are NOT medical doctors and that this application only serves as a theoretic case study for our software engineering approach.

## Overview
This health care BAN application can monitor vital signs such as blood sugar levels and heart rate, auto inject insulin through a pump device, or alert the hospital in case it is needed.
Furthermore, it can transmit aggregated monitoring data to the doctor at regular intervals and allows the doctor to remotely adjust the treatment plan.
OCL constraints are used to ensure that the application operates within its defined bounds.

## Instructions for Opening the Model
1. Download and install the [Eclipse Modeling Tools](https://www.eclipse.org/downloads/packages/) package.
2. (optional) Install the [UML Designer](http://www.umldesigner.org/) Eclipse plugin.
3. Clone [FogUML2Code](https://github.com/fog-uml-2-code/fog-uml-2-code).
4. Import the FogUMLProfile project from FogUML2Code into your Eclipse workspace (File -> Import -> Existing Projects into Workspace).
5. Import the HealthCareExample project from this repository into your Eclipse workspace.

The file `model.uml` contains the Eclipse UML2 model of the application.

The file `representations.aird` contains the diagrams designed with UML Designer.

The file `codeGeneration.properties` contains settings for the code generation.
