# arm-simulator
Project specifications:
Develop a web app using javascript 
Disasembly and simulation of 12 different Arm thumb instruction formats
Develop software interupt that allows the user to enter/print integer,string and characters, or terminate the program
In order to enter inputs for the program, the user should type his entries in the dialog box before uploading the file
The user should upload a file containing instructions in a binary format
The GUI is designed using the Bootstrap, a front-end framework
The app is designed to print the disassembled instructions as well as any changes in the registers values and print requested data
The program should terminate if the instruction ( 0xDEAD) is found
Assumptions:
Software interupt tasks:  
0 : Print integer
1 : Read integer
2 : Print string
3 : Read string 
4 : Read character
5 : Print character
Any other value should terminate the program
Memory size is 2M
Argument register: from r0-r3
Return values: r0-r1
