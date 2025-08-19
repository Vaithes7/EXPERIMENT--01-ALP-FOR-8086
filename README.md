# EXPERIMENT 01- ARITHMETIC OPERATION AND LOGICAL OPERATION IN 8086
# Name : Vaitheswaran N
# Roll no : 212224110059
# Date of experiment : 19.08.25





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
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


## Addition  of 8 bit ALP 
```
org 100h
mov ax,4535h
mov bx,733fh
add ax,bx
ret
```



## Output  
<img width="1371" height="544" alt="Screenshot 2025-08-19 083502" src="https://github.com/user-attachments/assets/ceb1fe40-bdb1-430d-aa4c-9242fadf2a77" />

 
## Subtraction   of 8 bit numbers  ALP
```
org 100h
mov ax,4535h
mov bx,733fh
sub ax,bx
ret
```
 
## Output  
<img width="1371" height="547" alt="Screenshot 2025-08-19 083721" src="https://github.com/user-attachments/assets/104b15a6-9f6e-48d4-997b-50eee9c3686e" />

## Multiplication alp
```
org 100h
Mov AL,74H
MOV BL,69H
MUL BL
HLT
ret
```
 ## Output  
 <img width="1366" height="556" alt="Screenshot 2025-08-19 084001" src="https://github.com/user-attachments/assets/d93ddc0a-c610-4d0e-83fe-6b64a0b85698" />



## Division alp 
```
mov al,68h
mov bl,18h
div bl
hlt
```

## Output  
<img width="1386" height="536" alt="Screenshot 2025-08-19 084124" src="https://github.com/user-attachments/assets/01c3478b-a2d0-40f1-a441-52f206064c2b" />

## AND
```
org 100h
MOV AX,2F11H
MOV BX,1125H
AND AX,BX
MOV [2000H],AX
```

## OUTPUT

<img width="1373" height="542" alt="Screenshot 2025-08-19 091059" src="https://github.com/user-attachments/assets/9c194db0-51df-4eec-922a-9748b3edb9c8" />


## XOR
```
org 100h
MOV AX,2F11H
MOV BX,1125H
OR AX,BX     
MOV [2002H],AX
ret
```
## OUTPUT

<img width="1370" height="536" alt="Screenshot 2025-08-19 091225" src="https://github.com/user-attachments/assets/0e945a45-833f-46e7-950c-3f917f04fe1f" />

## NOT
```
org 100h
mov ax,4535h
NOT ax
ret
```

## OUTPUT

<img width="1376" height="545" alt="Screenshot 2025-08-19 091337" src="https://github.com/user-attachments/assets/c2c2e3d8-4308-460c-8bde-76c7be04abdf" />

## EX-OR
```
org 100h
MOV AX,2F11H
MOV BX,1125H
XOR AX,BX     
MOV [2002H],AX
ret
```

## OUTPUT
<img width="1372" height="549" alt="Screenshot 2025-08-19 091413" src="https://github.com/user-attachments/assets/7cf68455-9b55-4ad6-8466-74ae903d29df" />




## Result :
 








