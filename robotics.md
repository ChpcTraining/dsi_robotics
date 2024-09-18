# What is programming?

Make an algorithm to do something in a specific language

programming.
● Algorithm: a procedure or formula for solving a problem.
● Programming language: artificial language designed to communicate instructions to a machine.

It also involves the process of designing, writing, testing, debugging, and maintaining the source code of a computer
program.

# What is Arduino? (I)

It's an open source electronics prototyping platform:

● Open source: resources that can be used, redistributed or
rewritten free of charge, often software or hardware.

● Electronics: technology which makes use of the controlled motion
of electrons through different media.

● Prototyping: an original form that can serve as a basis or
standard for other things.

● Platform: hardware architecture with software framework on which
other software can run.

# What is Arduino? (II)
The Arduino board is like a small computer that can be
programmed as many times as needed.

As a computer, it provides I/O interaction, through digital (input

and output) and analog input pins.

● Digital: discrete and finit, described in two states: 1/0, ON/OFF.

● Analog: continuous, can have infinite number of values.

The sketch made with the Arduino IDE is loaded to the board
and stored in the microcontroller.

More info at: http://arduino.cc/

# Parts of Arduino board

![image](https://github.com/user-attachments/assets/aaf650f8-6704-4389-a5ac-bf8135da3d2a)

![image](https://github.com/user-attachments/assets/50ac3996-03d0-4560-9356-a3d657b3ddf1)

# What is Scratch?

It's an open source and educational software focused mainly for
children, designed by the Lifelong Kindergarten group at MIT,
and implemented in Smalltalk (Squeak).

The programming instructions are pieces that have to be stick
each other in an order to form blocks and make a coherent
program, just like a puzzle.

More info and downloads at: http://scratch.mit.edu/

# What is S4A?

Scratch for Arduino (S4A) is a modified version of Scratch
ready for communication with Arduino boards.

An Arduino sketch (S4AFirmware) has to be loaded to the
board to work properly with S4A.

Both the installer and firmware can be downloaded from our
website: http://seaside.citilab.eu

![image](https://github.com/user-attachments/assets/36ef7b00-b901-4f74-b4df-ab0e89bd5a2b)

![image](https://github.com/user-attachments/assets/60412ca0-b6a5-4076-b52d-49a0e6711023)

![image](https://github.com/user-attachments/assets/9375cc42-1fc9-48c8-a221-a271f04751b2)

![image](https://github.com/user-attachments/assets/95aa271e-7829-4b42-a3d5-f5137c1d54d9)


![image](https://github.com/user-attachments/assets/6f56db4f-df78-43d0-a2ea-f07a6cbd16a4)

![image](https://github.com/user-attachments/assets/2b45299e-0ce0-48b0-8fa7-3d95d5e5a0b1)

![image](https://github.com/user-attachments/assets/b8b5938c-5ae8-4e79-a889-4cfb9b83b832)



![Uploading image.png…]()





## Other options

Arduino IDE

https://www.instructables.com/Electronic-Playground-With-Arduino-and-Scratch-2/

https://maker.pro/arduino/tutorial/how-to-program-an-arduino-with-the-scratch-programming-language-using-mblock

# Pin mapping in S4A:

● Digital read: digital pins 2 and 3.
● Digital write: digital pins 10, 11 and 13.
● Analog read: analog pins 0-5.
● Analog write: digital pins 5, 6 and 9.
● Servo control:
  ○ digital pins 4, 7 (continuous rotation).
  ○ 8 and 12 (standard).

# Basic electronics: Ohm's Law

Electricity if the flow of energy (electrons) through a conductive
material.

● Voltage (V): is the measure of electrical potential, measured in
Volts (V).

● Current (I): is the amount of flow through a conductive material,
measured in Amperes or Amps (A).

● Resistance (R): is the material's opposition to the flow of electric
current, measured in Ohms (Ω).

![image](https://github.com/user-attachments/assets/5d8b564d-dc71-44e2-9536-23c6a9e6f01c)

# Sample program: Blink

Comparison of a simple program that blinks a LED connected
to pin 13 on Arduino and in S4A. We can appreciate the
differences between the form and syntax of programming
languages ​​in both cases:

![image](https://github.com/user-attachments/assets/c3bb49c0-0c10-4a61-b474-e741d388b7e3)

# Online Arduino - Circuits

# Robotics Arm

# Servos

In this session we'll use servos for the first time. The mmain part of
the exercise is to create a robot hand controlled by the computer
keyboard. 

As shown in the diagram, each servo
has 3 wires: one red (5V), one black
(GND) and one yellow, which will be
connected to the pin we want to use
to send the order to the servomotor.
For this we have pins 4 and 7. As
you can see the assembly is quite
simple, just need a common point on
the board to connect the power of
each servo (red and black wires).
The diagram in next page includes a
pair of infrared sensors and an LED
to make it autonomous.

![image](https://github.com/user-attachments/assets/bbd78c55-f258-450a-96d7-4010cfaa1582)




