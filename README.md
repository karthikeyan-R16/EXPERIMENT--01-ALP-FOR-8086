# EXPERIMENT--01-ALP-FOR-8086
Name : KARTHIKEYAN R

Roll no : 212222240045

Date of experiment : 30/8/2024

## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
Components required: 8086 emulator
Theory
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.

# Running the Emulator :
1.Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory

2.Run emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color

3.write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION, DIVISION operations

4.Compile the program and check for the errors

5.Run (once there is no syntax error)

6.Click OK to see/view the output of your program on the Emulator screen.

7.After running the program, another menu screen will be displayed, where you have the option to “View” symbol table.

![image](https://github.com/user-attachments/assets/aac79516-97a5-40c5-b5ec-554670baafc9)


Click on emulate to start emulation

![image](https://github.com/user-attachments/assets/7476cfed-1bb1-45cf-9627-becd7d49912f)

If no errors are found click on run the program and check the status of various flags in the flags tab as shown below

![image](https://github.com/user-attachments/assets/1497709b-ceb0-440b-978f-20e075980b3f)


## Programs for arithmetic operations
### Addition of 8 bit ALP
```
org 100h

mov al,0046h 
mov bl,0056h
add al,bl
mov [6366h],al

ret
```
## Output

![image](https://github.com/user-attachments/assets/88a1f69b-cc10-46a4-92dc-7b7718e960f8)



### Subtraction of 8 bit numbers ALP
```
org 100h

mov ax,0046h 
mov bx,0056h
sub ax,bx;
mov [6378h],ax

ret
```
### Output

![image](https://github.com/user-attachments/assets/5849723c-5fba-459a-ae30-035437e2ca5f)


# Multiplication alp
```
org 100h

mov ax,0046h 
mov bx,0056h
mul bx;
mov [6367h],ax

ret
```
# Output
![image](https://github.com/user-attachments/assets/493f5017-8b5d-48ec-be85-1eacfe50161f)


## Division alp
```
org 100h

mov ax,0046h 
mov bx,0056h
div bx;
mov [6355h],bx

ret
```
### Output
![image](https://github.com/user-attachments/assets/d52b35cd-4b5b-483e-b811-ed52f4ca8bcf)


# OR Operation
```
org 100h

mov ax,0046h 
mov bx,0056h
or ax,bx

ret
```
# Output

![image](https://github.com/user-attachments/assets/bbf82afd-3089-4e9b-919a-253d0a14ad93)


# AND Operation
```
org 100h

mov ax,0046h 
mov bx,0056h
and ax,bx

ret
```
## Output
![image](https://github.com/user-attachments/assets/fd8c1f3c-431d-4bea-af62-514c4a5f53ae)



# NOT Operation
```
org 100h

mov ax,0046h 
not ax

ret
```
## Output

![image](https://github.com/user-attachments/assets/1d3ea6f0-09de-4f28-aaa0-a2dd8658154d)


# XOR Operation
```
org 100h

mov ax,0046h 
mov bx,0056h
xor ax,bx

ret
```
# Output

![image](https://github.com/user-attachments/assets/c7d02e46-13b2-455c-9a51-0c90d59fae12)


Result :
Thus, ALP for fundamental arithmetic and logical operations are executed successfully
