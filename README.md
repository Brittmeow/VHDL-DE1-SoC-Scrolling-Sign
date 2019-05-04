# VHDL-DE1-SoC-Scrolling-Sign
VHDL project created junior year of college while working with a DE1-SoC Development Board
Hardware: DE1-Soc FPGA Development Board (1 slider switch, 3 push buttons/keys, and 6 seven segment controls)
Functionality: A predefined clock is used in the design, running at 50Mhz that is used to clock in most of the values used in the design (Sw(0), key(1), key(2)). Sw(1) is used to control the speed at which the sign scrolls by; when sw(0) is a 1, the sign scrolls by at a slower, 2 second pace and when it is a 0 the sign scrolls at the normal one second pace. Key(0) is an asynchronous clear that sets the sign back to the beginning “EE4570” stage. Key(1), when pressed, enables the sign to scroll to the left instead of the default right shift. Key(2), when pressed stops the sign from scrolling and holds it at the current state.
