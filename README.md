# EX-01 EXPERIMENT--01-ALP-FOR-8086






```


Name : PRADEEP V
Roll no : 212223240119

```




## Aim: 





To Write and execute ALP on fundamental arithmetic and logical operations




## Components required: 



8086  emulator 



## Theory





Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. 
This application is able to run programs on both PC desktops and laptops. 
This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways:
backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple 
and easy to manage. There are five major buttons with icons 
and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to 
manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor
with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.






 ## Running the Emulator :

 

 

 
 


1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
3. write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 
4.	Compile the program and check for the errors 
5.	Run (once there is no syntax error) 
6.	Click OK to see/view the output of your program on the Emulator screen. 
7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 

![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)




9.	Click on emulate to start emulation
10.	

![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)


10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below
11.	

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
![WhatsApp Image 2024-08-28 at 23 35 41_e855412c](https://github.com/user-attachments/assets/fc417ad6-4112-4ba5-971c-43107dae08e4)




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
![WhatsApp Image 2024-08-28 at 23 33 40_bb1342e5](https://github.com/user-attachments/assets/7831dd2f-b3cc-4c7b-8889-ae839b82489c)






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
![WhatsApp Image 2024-08-28 at 23 37 28_8e96b3ce](https://github.com/user-attachments/assets/9772a31c-f3ca-4f59-a27a-10a994d5e582)






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
![WhatsApp Image 2024-08-28 at 23 38 42_2069a843](https://github.com/user-attachments/assets/0dcc97f9-e270-4c28-8b39-a41f2885189b)




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
![WhatsApp Image 2024-08-28 at 23 40 32_6beffc17](https://github.com/user-attachments/assets/1c278a9d-5c0b-4787-98ce-6f51318957f9)





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
![WhatsApp Image 2024-08-28 at 23 41 51_9c52c9ea](https://github.com/user-attachments/assets/ee30b55a-0328-46c6-8ebb-9ef30827226e)







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
![WhatsApp Image 2024-08-28 at 23 50 29_974e2ea4](https://github.com/user-attachments/assets/caceee4a-1d1c-4184-b8db-716c34d7adeb)





## NOT Operation

```
org 100h

MOV AX,4114H;
NOT AX;
MOV [8000H],AX;
ret
```









## Output
![WhatsApp Image 2024-08-28 at 23 44 18_83e8c269](https://github.com/user-attachments/assets/7a943875-b7a1-4d9c-961e-e479d102517c)




























## Result :
Thus, ALP for fundamental arithmetic and logical operations are executed successfully
 








