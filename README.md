  Build with Python-3.10.12, pyserial-3.5 
  Platform: ubuntu 22.04 
  
  for linux command :

  user$:cd /home/yourPATH/Python_Tkinter_Pyserial_TimerThreading/pMainPackage 
  
  user$:python3 main.py

  for windows command: 

  user$:python \yourPATH\main.py  

  You can create a batch file to launch more quickly.

  known issue: PySerial cannot determine whether a serial port has been occupied by this or another program.

  Timer Threading sometimes will conduct unexpeected error-> will take a look and fix soon

  20240214: Lunar New year has passed, add hex input function and fix some bugs

  ![alt text](https://github.com/Maxwell-lin-TW/Python_Tkinter_Pyserial_TimerThreading/blob/main/pyTerminal_20240214_demo.png)
  ![alt text](https://github.com/Maxwell-lin-TW/Python_Tkinter_Pyserial_TimerThreading/blob/main/pyTerminal_20240214.png)

  1. select desire serial port from this combobox. If it's empty please press "Scan" first. If still empty, you should check your connections of serial port cable.

  2. Press this button will enable connections with selected serialport.

  3. Scan all possible serial ports on your computer.

  4. Select desire baudrate. Default Parity=NONE, DATABITS=8, STOPBIT=1

  5. If too many text in the text area, press this to wipe out.

  6. Text area, for displaying received characters from serial ports.

  7. Transmitt text boxes, you can enter any characters to it, press the "Send" button next to it will start a one time transmittion.

  8. Send what ever you type in the text box aside.

  9. Time line mode, if selected, everytime serail port received characters, it will print out at text area with the time when received it.

  10. scroll to bottom. if selected, text area will automatically scroll to the end with the latest received characters.

  11. You can choose from this combobox to add line feed or carrage return or both with different kind.

  12. Hex mode, if selected, the text area will only display received characters in hex code with prefix '0x'

  13. Trear CR as LF. if selected, when receive from serial port, it will treat carrage return as a line feed.

  14. Hex input text field, please use following format, seperate each hex code with comma ',' or space ' '
  
      : 0x11,0x22,0x33,0x44  or 0xaa 0xbb 0xcc 0xdd

