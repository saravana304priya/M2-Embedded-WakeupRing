## DETAILED WORKING

 Whenever user place his finger over fingerprint module then fingerprint module captures finger image, and search if any ID is associated with this fingerprint in the system. If fingerprint ID is detected then LCD will show Attendance registered and in the same time buzzer will beep once.
Along with the fingerprint module, we have also used an RTC module for Time and date data. Time and date are running continuously in the system, so Microcontroller can take time and date whenever a true user places his finger over fingerprint sensor and then save them in the EEPROM at the allotted slot of memory.

User may download the attendance data by pressing and holding key 4. Connect supply to circuit and wait and after some time, LCD will show ‘Downloading....’.  And user can see the attendance data over serial monitor, here in this code software UART is programmed at pin PD7-pin20 as Tx to send data to terminal. User also needs a TTL to USB converter to see the attendance data over serial terminal.

And if the user wants to delete all the data then he/she has to press and hold key 2 and then connect power and wait for some time. Now after some time LCD will show ‘Please wait…’ and then ‘Record Deleted successfully’. These two steps are not shown in demonstration video given in the end.

