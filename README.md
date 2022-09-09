# EXPERIMENT--01-ALP-FOR-8086
Name    : SHAM RATHAN S
Roll no : 212221230093

## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator:
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.

## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 
![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)


9.	Click on emulate to start emulation 
![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)

10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 
![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)

## Programs for arithmetic  operations
### Addition of 8 bit ALP :
```
org 100h
MOV AH,03;
MOV BH,05;
ADD AH,BH;
MOV CX,AX;
MOV AX,0000H;
HLT;
```
### Output : 
![add](https://user-images.githubusercontent.com/93587823/189398764-10f058b7-7060-4c0a-919a-3bce525da362.png)
 
### Subtraction of 8 bit numbers  ALP:
```
org 100h
MOV AH,05;
MOV BH,03;
SUB AH,BH;
MOV CX,AX;
MOV AX,0000H;
HLT;T;
```
### Output :
![sub](https://user-images.githubusercontent.com/93587823/189398992-90bc41ba-e07c-4768-a27d-ba2f5719b645.png)
### Multiplication of alp:
```
org 100h
MOV AH,02;
MOV BH,04;
MUL BH;
MOV CX,AX;
MOV AX,0000H;
HLT;
```
### Output :
![mul](https://user-images.githubusercontent.com/93587823/189399516-3c91dcf7-31fd-4230-8119-37343911561f.png)
### Division of ALP:
```
org 100h
MOV AH,04;
MOV BH,02;
DIV BH;
MOV CX,AX;
MOV AX,0000H;
HLT;
```
### Output:
![div](https://user-images.githubusercontent.com/93587823/189399886-96686fc3-40e9-4562-a996-35bae9e15d7e.png)

## Result :
Thus, a program is executed on ALP for the fundamental arithmetic and logical operations successfully.
 








