Group Members

	Philip Mallory

	Robert Thackston

	Oudy Yang

Project Description

	Our proposal is to design and build a wearable physical activity monitor. The user’s activity is recorded by a pedometer and is visualized by an heart shaped LED array sewn into their t-shirt above the wearer’s breast. The activity metrics measured are number of steps taken since last reset and the instantaneous step rate. The number of steps taken is displayed by gradually shifting the color of the LED heart from red to green. The rate of steps (how active the user currently is) is displayed by displaying a throbbing animation on the LEDs using pulse width modulation. When the wearer is sedentary the heart will pulse slowly, when very active the heart animation will pulse rapidly.

	The device will be controlled by touch sensors (implemented as Darlington pairs) on the hem of the shirt. There will be a reset button which resets the step counter to zero and puts the device into Goal Setting mode. In this mode the user can press the increase and decrease touch sensors to enter their step goal. The input will be displayed on the heart.  The rows of the heart are incrementally lit as the user presses the increase button, and incrementally decreased as the decrease button is pressed. If the heart is fully lit the target is 40,000 steps, if half lit the target is 20,000 steps, and so forth. This interface scheme requires that each row of the heart be addressable rather than each individual LED.

	We will interface with the pedometer in a similar manner to this guy.

	We will sew the LEDs and other components to the shirt in the manner described by this lady.

Grading Criteria

	Information Display:

		Can the information display show progress to the goal?                25%

		Is the recorded data accurate?                            10%

		Is the information display attractive?                            10%

		Touch Interface:

		Does the touch interface respond to touch?                        15%

		Can the number of goal steps be set and reset?                    20%

		Is the touch interface usable and easily understandable?                10%

	Misc:

		Is the device comfortable to wear?                            10%

    Total:                                            100%

Extra Credit Ideas

    Individually addressable LEDs to enable more detailed information display and animation  10%

Bill of Materials

    * Pedometer - $10 - Amazon.com

    * 100  Bicolor LEDs (HMLP-4000) - $10.00 +s/h - Jameco

    * Conductive Thread - $10.95 + s/h - https://www.sparkfun.com/products/10120

	T-Shirt - $0 - Philip’s Closet

	Arduino Teensy

	Battery

	Miscellaneous components

