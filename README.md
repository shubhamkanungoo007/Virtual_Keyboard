# Virtual_Keyboard

This repository have the project to submit in Better Health Hackathon
# Step:1
Run the range-detector file first to mask the color you want to detect. 
In below line extra argument passed as " -f HSV -w" because it will use filters from "-f", HSV stands for Hue Saturation Value, and I was masking from webcam so "-w". We can use "-i" for an image.
> python3 range-detector.py -f HSV -w      


# Step :2
Run virtual-keyboard.py file it will show you the virtual keybaord and open the editor where you want to write. The key where pressed only when the masked object put onto the center of the square box of particular key.
This help us to reduce the touch of the common surface like keyboard because of COVID-19 virus spread from contact or touching common surface.
> python3 virual-kayboard.py
 
