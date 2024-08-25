# USB to CAN Termainal
At this point this is the Asynchronous terminal program from QT examples with a Line Edit feature added. It is intended to work the same as the line editor feature in QT.

- Backspace clears text
- Text is not sent until Enter/Return is pressed
- When text is sent no /r or /n is added.

The project is currently setup to run on Ubuntu. 

# Future Plans 

## USB Device management 

The key annoyance of the USB port is that it disappears from the device manager which in turn can cause the terminal to crash. One thing I would like to add is the type of autoconnect and reconnect feature you'd expect with any USB device. Mostly for the learning experience I should add. 

## More job specific 

Add buttons and controls that help with specific commands. 

- A command for setting Baud Rates
- A command for starting and stopping Sync
