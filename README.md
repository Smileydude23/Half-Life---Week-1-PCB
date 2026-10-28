hi this is my first time trying to design a pcb :D 
Introducing, the Smileybot...
It includes a small pet that you can interact with using two buttons. You can activate a play button and it will make a game of pong (FT3). There are also a variety of other options such as feeding and sleeping. 
I used KICAD to design both the schematic and the model for the PCB
The code was created in C++ through arduino IDE

BOM chart:
"Reference","Qty","Value","DNP","Exclude from BOM","Exclude from Board","Exclude from Simulation","Exclude from Position Files","Footprint","Datasheet"
"J1","1","Conn_01x04_Pin","","","","","${EXCLUDE_FROM_POS_FILES}","Imported Parts:Display_128x64_096_I2C",""
"J2","1","Conn_01x08_Pin","","","","","${EXCLUDE_FROM_POS_FILES}","Connector_PinHeader_2.54mm:PinHeader_1x08_P2.54mm_Vertical",""
"R1","1","10k","","","","","${EXCLUDE_FROM_POS_FILES}","Resistor_THT:R_Axial_DIN0204_L3.6mm_D1.6mm_P7.62mm_Horizontal",""
"SW1,SW2","2","SW_Push","","","","","${EXCLUDE_FROM_POS_FILES}","Button_Switch_Keyboard:SW_Cherry_MX_1.00u_PCB",""
"U1","1","XIAO-ESP32-C3-SMD","","","","","${EXCLUDE_FROM_POS_FILES}","Imported Parts:XIAO-ESP32-C3-SMD",""
"U2","1","DHT11","","","","","${EXCLUDE_FROM_POS_FILES}","Sensor:Aosong_DHT11_5.5x12.0_P2.54mm","http://akizukidenshi.com/download/ds/aosong/DHT11.pdf"
There is also the cost of PCB manufacturing but the shipping alone costs more than $30 so I left it out of budget, hope that's okay!

<img width="817" height="685" alt="Screenshot 2026-10-09 230156" src="https://github.com/user-attachments/assets/dcbaba3f-d8ca-45e7-ba86-efa82d9ddcd6" />
<img width="840" height="677" alt="Screenshot 2026-10-09 201229" src="https://github.com/user-attachments/assets/9b10470b-c785-44ac-afb4-75b3dc89541f" />
<img width="1037" height="456" alt="Screenshot 2026-10-09 190352" src="https://github.com/user-attachments/assets/d4512bf8-dd03-4d0f-aba3-4ae69afc43f4" />
<img width="1031" height="641" alt="Screenshot 2026-10-09 230509" src="https://github.com/user-attachments/assets/a00efd42-a3b8-4bf3-9386-7c2d998764a2" />
