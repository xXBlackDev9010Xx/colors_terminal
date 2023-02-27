# colors_terminal

## Installation

`pip colors_terminal`
##Usage

	from terminal.colors import Colors
	
	color = Colors()
	
	color.print(f"{color.red}Hello world!", colored=True)
	# Print text without color
	color.print("Hello world!", colored=False)
	# If colored is active the color will be seen if it is off it will not be seen
### Colors
→ black
→ white
→ blue
→ red
→ yellow
→ green
→ orange
→ purple