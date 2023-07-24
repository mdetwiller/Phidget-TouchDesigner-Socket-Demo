# Phidget-TouchDesigner-Socket-Demo
A simple example of using a socket (hosted by the Phidget driver) to bring Phidget data into TouchDesigner without interrupting the main Python thread

# Requirements
- Phidget Control Panel/Drivers https://www.phidgets.com/docs/Phidgets_Drivers
- Phidget Python Module (Phidget22)
- Phidget device-specific code sample https://www.phidgets.com/?view=code_samples&lang=Python

# To run Socket.25.toe example
1. Copy the file path to the folder containing your installed Phidget22 module.
2. Open the Phidget Control Panel and configure the Phidget's port. Quit the Control Panel or else TouchDesigner won't be able to connect to the Phidget.
3. Select the TCP/IP DAT and populate the Local Address field with the suggested IP address
4. Edit the Execute DAT so that myPath (line 9) matches the file path from Step 1, TCP_IP (line 20) matches the Local Address in the TCP/IP DAT, and TCP_PORT (line 21) matches the port value set in Step 2.
5. Save these changes and restart the .toe file.
