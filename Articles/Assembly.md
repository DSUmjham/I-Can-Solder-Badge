

# Badge Assembly
Make sure you've got a good grasp on the components you are working with and soldering safely before starting this!

The order of assembly is not critical, but this approach should work well:
 1. Verify you have all of the parts needed:
	 1. Badge PCB
	 2. [Battery (CR2032)](https://docs.google.com/viewer?url=https://github.com/DSUmjham/I-Can-Solder-Badge/raw/main/Datasheets/CR2032.pdf)
	 3. [Battery Holder](https://docs.google.com/viewer?url=https://github.com/DSUmjham/I-Can-Solder-Badge/raw/main/Datasheets/BAT-HLD-001-THM.pdf)
	 4. [Pushbutton (x2)](https://docs.google.com/viewer?url=https://github.com/DSUmjham/I-Can-Solder-Badge/raw/main/Datasheets/MJTP1230.pdf)
	 5. [White LED](https://docs.google.com/viewer?url=https://github.com/DSUmjham/I-Can-Solder-Badge/raw/main/Datasheets/QBL8IW30C-CW.pdf)
	 6. [Blue LED](https://docs.google.com/viewer?url=https://github.com/DSUmjham/I-Can-Solder-Badge/raw/main/Datasheets/C503B-BCN-CV0Z0461.pdf)
![Badge components labeled](https://github.com/DSUmjham/I-Can-Solder-Badge/raw/main/Images/assembly01.jpeg?raw=true)

2. Install the battery holder. This is the only piece inserted through the back side of the circuit board and soldered on the front. The curved edge should be oriented towards the top of the badge.

   **Hint:** When soldering, place something under the badge, like the battery, to keep it from rocking.

   ![Battery holder](https://github.com/DSUmjham/I-Can-Solder-Badge/raw/main/Images/assembly02.jpg?raw=true)
   ![Soldering battery holder](https://github.com/DSUmjham/I-Can-Solder-Badge/raw/main/Images/assembly03.jpg?raw=true)

3. From here on out, everything other component is inserted through the front of the badge and soldered on the back side.

4. Next, install the pushbuttons to the **SW1** and **SW2** spots on the PCB. The pinouts of the buttons are rectangular and will only fit onto the badge one way. You should not need to bend any pins to get the buttons to fit.
![Pushbuttons](https://github.com/DSUmjham/I-Can-Solder-Badge/raw/main/Images/assembly04.jpg?raw=true)
![Soldering pushbutton](https://github.com/DSUmjham/I-Can-Solder-Badge/raw/main/Images/assembly05.jpg?raw=true)

5. Determine which LED is which. Since both LEDs are clear, test them with the battery to see their colors. Place the long lead of the LED (positive/anode) on the positive side of the battery and the short lead (cathode/negative) on the other side. If it doesn't light up, flip it around.
![LEDs on battery](https://github.com/DSUmjham/I-Can-Solder-Badge/raw/main/Images/assembly06.jpg?raw=true)

6. Solder the white LED onto the badge. The shorter lead of the LED is the negative side (cathode). This should go through the square pad on the left-hand side of **D1** or **D2**; the two spots are interchangeable. Another way to check is to ensure the LED’s flat edge aligns with the silkscreen’s shape.
![LEDs](https://github.com/DSUmjham/I-Can-Solder-Badge/raw/main/Images/assembly07.jpg?raw=true)
![Solder white LED](https://github.com/DSUmjham/I-Can-Solder-Badge/raw/main/Images/assembly08.jpg?raw=true)

7. Solder the blue LED into the remaining spot on the badge (**D1** or **D2**). Again, the shorter lead (cathode) will go through the square solder pad.
![Solder blue LED](https://github.com/DSUmjham/I-Can-Solder-Badge/raw/main/Images/assembly09.jpg?raw=true)

8. Using a sidecutter, trim the leads of the LEDs. You do not need to trim any of the other components.
![Trim LED](https://github.com/DSUmjham/I-Can-Solder-Badge/raw/main/Images/assembly10.jpg?raw=true)

9. Install the battery. The negative side of the battery will touch the PCB, and the positive side will rest against the battery holder.
![Battery](https://github.com/DSUmjham/I-Can-Solder-Badge/raw/main/Images/assembly11.jpg?raw=true)