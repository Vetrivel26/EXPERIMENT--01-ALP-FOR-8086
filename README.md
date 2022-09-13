# EXPERIMENT--01-ALP-FOR-8086
Name : VETRIVEL.S
Roll no :212221240060

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
name "ADDITION" org 100h MOV AH,05H; MOV BH,02H; ADD AH,BH; MOV CH,AH; MOV AH,0H; MOV BH,0H; HLT;


## Output  
AH and BH registers for ADDITION
![1](https://user-images.githubusercontent.com/95363138/189950324-4144ae93-dc4f-4aac-92a7-d31cb9c2791e.jpeg)

Performing 8 Bit ADDITION
![2](https://user-images.githubusercontent.com/95363138/189950413-f6124ec6-f5db-49d3-9bb0-7fb51b155b41.jpeg)

Moving to CH register
![ch register](https://user-images.githubusercontent.com/95363138/189950491-60580159-f813-4f8f-8935-474addf832bc.jpeg)

Resetting AH,BH register and Execution
![AH BH](https://user-images.githubusercontent.com/95363138/189950540-2797a099-3c22-4b31-8ba9-e197c2d32fc2.jpeg)

Flags:

![flags](https://user-images.githubusercontent.com/95363138/189950559-40dca66c-c92f-4961-bb10-b9d77efc1d95.jpeg)

## Subtraction   of 8 bit numbers  ALP 
name "SUBTRACTION" org 700h MOV AH,7H; MOV BH,5H; SUB AH,BH; MOV CH,AH; MOV AH,0H; MOV BH,0h; HLT;

## Output  
AH and BH registers for SUBTRACTION
![ah bh sub](https://user-images.githubusercontent.com/95363138/189950862-058b9422-47a6-414f-a37e-25a396c629c2.jpeg)

Performing 8 Bit SUBTRACTION
![8bit sub](https://user-images.githubusercontent.com/95363138/189950880-5bca64dd-bbd2-4d9c-bc58-1f771dd920cb.jpeg)

Moving to CH register
![mov ch](https://user-images.githubusercontent.com/95363138/189950911-7561294b-2620-4c19-a793-89d2ad3b124b.jpeg)

Resetting AH,BH register and Execution
![ah bh res](https://user-images.githubusercontent.com/95363138/189950941-85cd2d27-b0fa-4f5b-a741-5df3ee4c6d77.jpeg)

Flags:

![flags 2](https://user-images.githubusercontent.com/95363138/189950966-4c53fb7d-b8d0-4d60-8696-95a25a8c4b9a.jpeg)

## Multiplication alp 
name "MULTIPLICATION" org 700h MOV AX,5H; MOV BX,4H; MUL BX; MOV CX,AX; MOV AX,0H; MOV BX,0h; HLT;

## Output  
AX and BX registers for MULTIPLICATION
![ax bx mul](https://user-images.githubusercontent.com/95363138/189951658-5c6fd528-c840-4536-a91e-8ec44d934f38.jpeg)

Performing 8 Bit MULTIPLICATION
![8bit mul](https://user-images.githubusercontent.com/95363138/189951694-6ee8f766-f720-4c55-8fc2-648fb61062f9.jpeg)


Moving to CX register
![mov cx](https://user-images.githubusercontent.com/95363138/189951713-d2a3658f-f5ec-49e2-83dd-d04416d45342.jpeg)

Resetting AX,BX register and Execution
![ax bx](https://user-images.githubusercontent.com/95363138/189951739-446f15ea-9342-49ee-9230-1c393aab6e76.jpeg)

Flags:
![flag 3](https://user-images.githubusercontent.com/95363138/189951780-6dc350f6-ac0d-4f14-93d6-c7936e5afb9c.jpeg)


## Division alp 
name "DIVISION" org 700h MOV AX,9H; MOV BX,3H; DIV BX; MOV CX,AX; MOV AX,0H; MOV BX,0h; HLT;
## Output  
AX and BX registers for DIVISION
![ax bx](https://user-images.githubusercontent.com/95363138/189953509-90441d0c-0b71-4b1c-a508-4a1657cc449e.jpeg)

Performing 8 Bit DIVISION
![8 bit div](https://user-images.githubusercontent.com/95363138/189953100-13560bf4-e7f7-47e6-87bc-1bf7acf12330.jpeg)


Moving to CX register
![cx div](https://user-images.githubusercontent.com/95363138/189953165-afe0c85a-7a6b-4d22-b33f-001e2901e26b.jpeg)

Resetting AX,BX register and Execution
![ax bx DIV](https://user-images.githubusercontent.com/95363138/189953193-6af07174-9b85-4e55-bc13-c0c6a74c3b94.jpeg)

Flags:
![flag 4](https://user-images.githubusercontent.com/95363138/189953226-cd800560-a108-440d-b2e7-99db575d613d.jpeg)

## Result :
 Thus a program on ALP for the fundamental arithmetic and logical operations is done successful.








