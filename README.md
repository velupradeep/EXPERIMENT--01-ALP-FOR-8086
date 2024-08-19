# EX-01 EXPERIMENT--01-ALP-FOR-8086
```
Name : PRADEEP V
Roll no : 212223240119
Date of experiment :19.08.2024
```
## Aim: 
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 
8086  emulator 
## Theory
```
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. 
This application is able to run programs on both PC desktops and laptops. 
This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways:
backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple 
and easy to manage. There are five major buttons with icons 
and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to 
manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor
with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.

```
 ## Running the Emulator :
 ```
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
3. write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
4.	Compile the program and check for the errors 
5.	Run (once there is no syntax error) 
6.	Click OK to see/view the output of your program on the Emulator screen. 
7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 

![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)


```




9.	Click on emulate to start emulation 





![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 


![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)



## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
org 100h

MOV AX,05H;
MOV BX,04H;
ADD AX,BX;
MOV [1000H],AX;

ret
```
## Output  
![image](https://github.com/user-attachments/assets/bfde8fea-f186-42cd-a0d9-5d0bcdf73cfe)

 ## Subtraction   of 8 bit numbers  ALP 
```
org 100h

MOV AX,06H;
MOV BX,03H;
SUB AX,BX;
MOV [2000H],AX;
ret
```
 ## Output  
![image](https://github.com/user-attachments/assets/cf88b7f4-1f4a-4d57-affb-cecbbc1579a1)

## Multiplication alp 
```
org 100h

MOV AX,02H;
MOV BX,02H;
MUL BX;
MOV [3000H],AX;
ret
```
## Output  
![image](https://github.com/user-attachments/assets/4ade0491-7b68-493f-9b3e-9c5a01c99e45)

## Division alp 
```
org 100h

MOV AX,08H;
MOV BX,04H;
DIV BX;
MOV [4000H],AX;

ret
```
## Output 
![image](https://github.com/user-attachments/assets/0a364563-4074-4501-9d58-54edd248e4ce)

## OR Operation
```
org 100h

MOV AX,4114H;
MOV BX,5001H;
OR AX,BX;
MOV [5000H],AX;
ret
```
## Output
![image](https://github.com/user-attachments/assets/20c96cc7-0d7e-45b0-85a9-bda9930c116e)

## AND Operation
```
org 100h

MOV AX,4114H;
MOV BX,5001H;
AND AX,BX;
MOV [6000H],AX;

ret
```
## Output
![image](https://github.com/user-attachments/assets/433b3db4-0d2f-4609-9258-c3374a5bf724)

## XOR Operation
```
org 100h

MOV AX,4114H;
MOV BX,5001H;
XOR AX,BX;
MOV [7000H],AX;
ret
```

## Output
![image](https://github.com/user-attachments/assets/0e6656a3-9a9c-46a4-b81c-706f8e566a6b)

## NOT Operation
```
org 100h

MOV AX,4114H;
NOT AX;
MOV [8000H],AX;
ret
```

## Output
![image](https://github.com/user-attachments/assets/f48ce567-ebf4-4328-971c-53bcf313be3f)





## Result :
Thus, ALP for fundamental arithmetic and logical operations are executed successfully
 








