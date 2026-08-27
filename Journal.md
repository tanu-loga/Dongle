# Overview

## August 27th, 12:05 PM AEST
Started this YSWS. I have till tomorrow 3am to finish this. Just downloaded KiCad.  
I hope this goes well!  
3 mins by, I opened my schematic. No idea what that means. Currently reading the sentence again and again. 
I think I understood it!! This is actually my first foray into the hardware side. I've got alot to learn. Thankfully, my typing speed is quite fast so writing this won't take me much time as one might think.  
NOTES TO MYSELF:  
Dongle is something like a device to be plugged into something. Theres wifi dongles and whatnot?  
PCB is basically a part within the dongle. USB for example has a small pcb, which does stuff.  
Schematic is the architectural plan of something.  
PCB shows how stuff will be connected irl while Schematic shows the pretty version. I can also think of it [schematic] as the 'envisioning board'.  
  Schematic is how you want life to turn out while PCB is how life actually turns out. Atleast become a Dongle to be useful  
 -Sun Tzu, Ragebaiter  
Woah, I actually wrote that. 
## 12:35 PM 
I am currently reading a guide to PCB electronic parts. Diving straight into this YSWS without any hardware knowledge is as great as diving into water without learning how to swim. The given guide already assumes I'm atleast slightly aware of what is happening. The best I can do is understand and be able to describe each component in one line without looking. I'm glad I chose this ysws, this is teaching me more than I ever learnt in science class.   
I should eat breakfast soon and do the actual schematics after that. Only had coffee and biscuits since waking up at 10 AM. Okay, back to studying PCB!  
YOU CAN DO IT, MYSELF!
## 12:48 PM
I reckon writing on Github lets me retain memory. I still perfectly remember what schematic and PCB means. I'll write the definitions here to remember it better + reference it + you can reference it. Yes, I really am gonna write it myself. Warning for many anime/manga references. Also, lets see how many points out of 100 I have left when I finish writing the terms.   
PCB- Printed Circuit Board. DA PLACE where everything happens. Its green usually. The place where it all starts, the PCB arc   
Components- The citizens of PCB city. All need and emit cursed energy aka electricity. Too much cursed energy? Cursed spirits will come and finish em. Too little? They aint gonna work   
VBUS- It is through the VBUS electricity comes and makes stuff work. Usually 5 volts. Also the main character of the story. -2 points because I'm unsure of this and I don't remember the full form 
Plug- Bro needs a port to plug into
Port- Bro needs a plug to be useful. AKA a socket 
GND- Ground aka Asta's sword. It is the return point of electricity. Usually 0 volts? Asta's sword because it 'returns input', something like how his sword deflects magic while it has no magic itself  
Resistor- Stops/reduces cursed energy, like a speedbump or a shield  
I need to reference dictionary because I can't remember. -5 points from 100. 
## 1:04 PM
Still writing the dictionary terms.   
Capacitator- Bro stores electrical current           
Trace- Bro is the road itself, through which electricity travels. Its made of copper   
IC- Forgot full form. -2 points for forgetting form and definition         
IC- Integrated circuit -it is a silicon piece with thousands of tiny electronic circuits    
Pad- Parking spot for the component's leg. It is an area where a component rests       
VCC- Positive power supply. Basically a flare for saying that it needs power here   
Footprint- Two pads signalling where something should go. AKA parking lot    
## 1:12 PM
-5 points for referencing dictionary. 
Transistor- Switch which is used for controlling power supply         
Diode- One way road where electricity flows one way   
LED- Light Emitting Diode. Diode wanted to become an LED! Boring definition is a diode which emits light once electricity is passed through it    
Layers- PCB has multiple layers. The initial one, copper, another one, copper and that green thing again.   
Via- A hole in which electricity passes through layers    
## 1:19 PM 
Going to eat breakfast! Break I guess                 
## 1:58 PM
I am back!    
Connector- Connects stuff together   
USB A- main USB which powers the whole stuff   
USB D-, USB D+ - USB data connections. They carry USB data communications AKA USB telephones  
Datasheet- A sheet by manufacturer explaining how components work, apparently I should eventually love it or learn to tolerate it    
Silkscreen- The printed text and labels on PCB explaining what part is what like R1, C1 and so on       
J1, J2 and so on- Used for connectors
U1, U2 and so on- Used for integrated circuits or chips
R1, and so on- For resistors. The list goes on but I think just seeing the capital letter would help aside from these cases    
I'm done!! I listed all the beginner vocab!!    
How many points do I have now?  74.. Yes I did not list some of the mistakes I made but I did look up the dictionary 3-4 times.  
The only challenge is myself and lets see how much points I get the next time I build a similar project like this   
Now, ONTO THE ACTUAL THING!  
## 2:12 PM
Doing the schematics!
## 2:36
Took me 20 mins for the first four steps. Ctrl Y doesn't work. Wire stops wiring when I double click. 
I had a minor issue finding the MCU download. I reckon it was because the file type was not selected. Turns out I can just specify format and click it without needing to name it and all. Here's how mine looks for now:  
<img width="987" height="714" alt="image" src="https://github.com/user-attachments/assets/9a350ca0-6793-4407-a4fb-c7c1eecc00d7" />

Note to self- Learn what MCU actually does
