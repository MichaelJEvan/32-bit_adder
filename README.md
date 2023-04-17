# 32-bit_adder[Read Me Adder Circuits.pdf](https://github.com/MichaelJEvan/32-bit_adder/files/11254834/Read.Me.Adder.Circuits.pdf)

![Screenshot 2023-04-17 at 3 04 30 PM](https://user-images.githubusercontent.com/49410936/232586094-258b8667-0ab6-4e3b-868d-cda1d3906ec2.png)



Note: All the circuits created for this project were done with the program “Digital” as per our previous discussions. They will not run on any other application to my knowledge. The files are recognized by their .dig extension.


The two main files to run are: 32_bit_adder.dig & Final_4bit_add_sub.dig


https://github.com/hneemann/Digital


IMPORTANT: All files for this assignment must remain in the folder provided! Removing or moving any files from the final project folder “CIS323_Assign2_mevan” will not allow the final circuits to run. They run as a package. The program looks for all initial circuits created that are utilized in larger circuit projects so removing any from the folder renders the newly created circuit inoperable and components may not appear in the circuit.


Warning: Do not save the folder on your Desktop or in the “Digital” software package folder. For some reason the program does not recognize folders created on my desktop or its own application folder, but does everywhere else. Not sure why.
Note: I do all my development on an M1 MacBook Pro. All the circuits run without issue on my computer. If you have any difficulty running them please call me at cell: 570-947-9446 at your convenience if needed.


Full Adder: this was initially created per the instructors instructions for the assignment. I then created an 8-bit adder to test the Full Adder circuit for functionality when daisy chained together for larger circuit design. The Cin & Cout are required for the circuit to run. Cin is set to 0 and is the Carry bit for subsequent Full_Adder circuits....Cout being the Carry bit.

![Screenshot 2023-04-17 at 2 58 47 PM](https://user-images.githubusercontent.com/49410936/232585333-e05eb6d4-ac6e-47b4-849c-38e0214fea2e.png)

![Screenshot 2023-04-17 at 2 59 48 PM](https://user-images.githubusercontent.com/49410936/232585354-52d7c789-58b3-4551-b3a3-82fc2b203811.png)

The 32-bit Binary Adder Circuit below was created utilizing 4 of the above 8-bit adder circuits. Right clicking on any of the “designed circuits” pulls up the underlying architecture of the circuit if you choose to do so and can also be run from their pop-up window if desired. I changed the initial Cin to a Constant input 0 in this circuit provided by the software rather than an input switch. This is set to a constant of 0.
The software itself unfortunately does not provide 1’s & 0’s to be indicated on the input & outputs, only Light & Dark. Their indications are as follows: Light = 1 & Dark = 0 The Y input is read across the top row and X, the row below.

![Screenshot 2023-04-17 at 3 02 02 PM](https://user-images.githubusercontent.com/49410936/232585470-05ae752c-daab-4d15-b741-07524cb489be.png)

Exercise 2: This was built utilizing 4 Full Adder circuits and a mux preceded by a Not, this flips the bits for subtraction. The initial circuit was then miniaturized to a custom circuit and utilized for the final circuit design.
When the “subtract” input is dark it is in “addition mode”. Depressing and lighting the subtract input converts the circuit into “subtraction mode”. Per instructions, Negative and Overflow are not accounted for in this exercise.

![Screenshot 2023-04-17 at 3 03 12 PM](https://user-images.githubusercontent.com/49410936/232585742-c681c298-3dc7-41c0-a4e5-6f4bc50f11fe.png)
