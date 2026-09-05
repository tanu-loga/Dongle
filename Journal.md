# Overview
Total time 16~ hours!       
If you don't count me learning what pcb meant, -2 hours.          
All calculation with a buffer of 30 mins-              
I spent 8 hours on breaks - not including sleep               
2 hours on purely learning what stuff meant (resistors and so on).                
5-6 hours on the schematics - yes, im slow and I didn't realise what it meant                   
6 hours on the PCB wiring and so on                           
I spent 1-2 hours on the case - installing took alot of time and I tried to tinker with the case alot. I tried but I thought it took too much time so I gave up                     
1 more hour for the BOM. Really, I had no experience making the BOM and I did not think it would take an hour               
The Dongle turns LED on when button is pressed and opens my github!  
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
 Tanu from 3:21 PM writing: Ground is actually a reference point for electricity. You can't just outright say something is [number] volts. You need to measure it relative to something. So VBUS is 5 volts because VBUS - GND (0 volts) = 5. Another thing is that it is often the return path. To make ya and myself better understand the return thing, here's a diagram I made- 
 
<img width="850" height="752" alt="image" src="https://github.com/user-attachments/assets/d3695851-775f-4a14-a5b2-834b5bc7c21d" />


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
## 3:03 PM
I forgot to look up MCU and instead looked this up-
<img width="1559" height="118" alt="image" src="https://github.com/user-attachments/assets/7bd2b696-005e-4825-997c-9ad6e1fcb142" />
Yeah, the guide dropped that outa nowhere.
What the hell is nF, decoupling capacitor, noise?? Electric stuff like these emit noise??   
Anyways the simplified version is just a capacitator which is near a chip aka IC to keep its power supply stable. When chip bro needs extra power supply suddenly, this capacitator helps. Also, power supply ain't so stable as a straight line. It has its bumps and dips. Those unwanted wobbling is called noise. 100 nF stands for nanoFarads, which is used for measuring capacitance - which I presume is the amount it can store. Also 100nF isn't a magical number, its just a common value. 
Unpolarised means the negative and positive end of the capacitator isn't specified. Thank you, unpolarised, one less work to do!  
I'm surprised and happy that I'm starting to understand more of this considering I've never even touched hardware.
## 3:56 PM
This is what I have so far:   
<img width="797" height="550" alt="image" src="https://github.com/user-attachments/assets/8901d4f7-7871-4721-b4b6-1de137bfe5dc" />

## 6:06 PM
I took a break, ate, played games. Now I have to go outside and buy coffee.
## 7:00 PM
Started PCB again, I should understand terminology more. What does 3V3 mean...
## 8:26 PM
Looked up ideas for making my LED more interesting. Here's how it looks so far-
<img width="946" height="649" alt="image" src="https://github.com/user-attachments/assets/adc41ab7-36d1-4a4e-81e6-acde9d535865" />        

Break time again..
## 10:44 PM
Watched a movie halfway through and exactly before a fight scene (I assume). The movie is called Rorouni Kenshin: Kyoto Inferno - its the part two of a series of movies - and its PEAK. Anyways, back to PCB and brainstorming. I also had dinner!
## 10:59 PM
I wired the basic stuff, now all I need to do is assign an LED or something else for each port. I think one of the port having a button in which I can open my browser with one click will be nice. Here's what I have so far-
<img width="975" height="721" alt="image" src="https://github.com/user-attachments/assets/1ce44365-092a-4304-a23d-c164aaff7771" />           
Yes, I know that SW button is floating without getting connected. I'm wondering what port I should connect it too.
## 11:20 PM
I'm so sleepy and am currently researching how to wire a button. I asked the org for a time extension. Here's how the schematic looks-
<img width="1363" height="605" alt="image" src="https://github.com/user-attachments/assets/500a259d-d15d-449a-871e-5d6e65c9c138" />

Waiting ten minutes for their reply! Till then I'll get ready to sleep.

## August 28th, 9:09 AM
Had a good night's sleep and woke up to see the ysws was extended! YAY!!!

## 9:33 AM
Okay, so I had about 3 errors and 3 warnings with my schematic. I rewired them but it's not working. I also have to check if my sw_push button will work, but it shows no errors as of now.
<img width="1686" height="881" alt="image" src="https://github.com/user-attachments/assets/b923e877-ff03-4804-a9d5-02f4455b049b" />
## 9:47
Guess what was the fix? We need to add a PWR_FLAG to signify its a power source. It wasn't mentioned in the guide so I couldn't figure out what in heavens was the fix. Thanks to @phantom-ascii, the problem was solved. 3 more warnings are left, but it can be fixed when I'm designing the PCB (phantom-ascii said so). 
<img width="1918" height="1016" alt="image" src="https://github.com/user-attachments/assets/fe1de530-487c-4023-8cd5-8a2c409c62e2" />

After this, I had to assign footprints. So I looked in the top bar as specified in the guide and clicked this option-
<img width="1873" height="203" alt="image" src="https://github.com/user-attachments/assets/cd7ceb9a-9faf-488f-97bb-f0f2afc89780" />

BUT I couldn't normally assign footprints! What was the fix? Turns out its a fake assign footprint that does something else. The actual one was under Tools in the top top bar. Nice interface, Kicad!
Now I have to assign footprints.

## 11:01 AM
I have to assign footprints for UBS_A and the YSWS guide provided a zip file for it. I unzipped it and tried to find it in the assign footprint section. Didn't work. But thanks to @shadow and @phantom.ascii, we did something and it worked in the PCB editor. Turns out the file name was indeed correct. I have about 4 hours to finish this.
<img width="1914" height="975" alt="image" src="https://github.com/user-attachments/assets/632c2447-be12-453b-8618-935f77155545" />
## 11:37 AM
Looking good enough so far:
<img width="1919" height="995" alt="image" src="https://github.com/user-attachments/assets/adbac630-9646-407c-b34d-8e9909be7600" />
## 12:48 PM
Finally finished the full layout-        
<img width="397" height="743" alt="image" src="https://github.com/user-attachments/assets/086915d2-561a-4e04-89b4-0b0aed04864e" />
## 2:09 PM
Locked in and kinda finished wiring!                 
<img width="1918" height="1002" alt="image" src="https://github.com/user-attachments/assets/530a531a-d84d-4e3b-9790-3d6d5ae77d17" />
## 2:55 PM
Almost done except for the GND wiring              
<img width="1409" height="881" alt="image" src="https://github.com/user-attachments/assets/e5c8dbde-2fef-410a-8b34-cf0f494ace29" />

## 3:21 PM  
ITS DONE. THE PCB IS DONE! 0 ERRORS FROM WIRING!                          
<img width="483" height="777" alt="image" src="https://github.com/user-attachments/assets/359b490d-aef7-4bd6-9cfe-5d6a8bc5edb0" />

Until now I was under the plan of not adding a case, but I think given that they extended my time, I can add a case!
## 3:59 PM 
Finally downloaded and set-upped Fusion 360, which is used by the guide. It was easily the HARDEST application to download!
## 4:11 PM
Started working on the case!
<img width="1436" height="635" alt="image" src="https://github.com/user-attachments/assets/cb2ca045-a805-48b1-b53f-f0fbf7444e6c" />

## 4:27 PM
Lunch break!
## 5:13 PM
Finished everything and did not add case. Currently doing BOM
## 5:49 PM
Finished the whole YSWS!!

## August 29th 8:20ish, but am writing this on September 1st
Did some changes and upon the feedback of peers and org, I changed the board outline so that the usb edge connecter will fit into the computer. I also added a 'T' as some sort of a signature. 
About the case, I thought I had time but I gave up since I'm quite new to fusion last time.

## September 3rd, 1:39 PM
Did more changes including changing the wiring since it was on the edge of the pcb
Here's the updated PCB!

<img width="656" height="842" alt="image" src="https://github.com/user-attachments/assets/617f98a9-0e52-4817-9d98-5ca4e09ff565" />

## September 5th, 1:48 PM
Doing BOM again

## 2:26 PM
JLCPCB BOM Tool - BOM Matching																
BOM name：kicad lcsc-JLCPCB Assembly Order.xlsx			Download Time：2026-09-05 12:25:14				"* Our matching results are updated in real-time, but stock and prices may change. 
If it's been over 24 hours, please re-match before placing your order."									
PCB Assembled Qty：5			Est. Total Price：2.6300													
Your BOM				Matched Parts							Order Information					
Designator	Comment	Footprint	JLCPCB Part #	Matches	Part # 	Manufacturer	Footprint	Description	Category	Warning	JLCPCB Part #	Product link	Lib Type	Qty	Source	Total Price ($)
C1,C2	Capacitor_SMD:C_0603_1608Metric	100nF		Select by System	CC0603KRX7R9BB104	YAGEO	0603	100nF 50V X7R ±10% 0603 Multilayer Ceramic Capacitors MLCC - SMD/SMT ROHS	Multilayer Ceramic Capacitors MLCC - SMD/SMT		C14663	https://jlcpcb.com/partdetail/YAGEO-CC0603KRX7R9BB104/C14663	Basic	20	20 JLCPCB	0.276
D1,D2,D3,D4,D5,D6,D7,D8	LED_SMD:LED_0805_2012Metric	LED		Select by System	KT-0805R	Hubei KENTO Elec	0805	-40℃~+85℃ 120° 2.4V 210mcd 40mW 615nm~630nm 645nm Discrete Diode Red Water Clear 0805 LED Indication - Discrete ROHS	LED Indication - Discrete		C2295	https://jlcpcb.com/partdetail/Hubei_KENTOElec-KT0805R/C2295	Extended	26	26 JLCPCB	0.299
J1	CH552G:USB-A	USB_A		Select by System	USB-05	SOFNG	插件	-35℃~+75℃ 1 18.75mm 1A 24V 4P Male Right Angle Type-A USB 2.0 插件 USB Connectors ROHS	USB Connectors		C112454	https://jlcpcb.com/partdetail/SOFNG-USB05/C112454	Extended	2	2 JLCPCB	0.161
R1	Resistor_SMD:R_0603_1608Metric	10K		Select by System	0603WAF1002T5E	UNI-ROYAL(Uniroyal Elec)	0603	-55℃~+155℃ 100mW 10kΩ 75V Thick Film Resistor ±1% ±100ppm/℃ 0603 Chip Resistor - Surface Mount ROHS	Chip Resistor - Surface Mount		C25804	https://jlcpcb.com/partdetail/26547-0603WAF1002T5E/C25804	Basic	20	20 JLCPCB	0.08
R2,R3,R4,R5,R6,R8,R9,R10	Resistor_SMD:R_0603_1608Metric	330R		Select by System	0603WAF3300T5E	UNI-ROYAL(Uniroyal Elec)	0603	-55℃~+155℃ 100mW 330Ω 75V Thick Film Resistor ±1% ±100ppm/℃ 0603 Chip Resistor - Surface Mount ROHS	Chip Resistor - Surface Mount		C23138	https://jlcpcb.com/partdetail/23865-0603WAF3300T5E/C23138	Basic	26	26 JLCPCB	0.0702
SW1,SW2	Button_Switch_SMD:SW_SPST_TS-1088-xR020	SW_Push		Select by System	TS-1088R-02026	XUNPU	SMD,4x3mm	100,000 cycles 12V 2.6N 2.93mm 2mm 3.9mm 50mA Black Round Button SMD(SMT) Tab SPST Surface Mount,Vertical Without Bracket SMD,4x3mm Tactile Switches ROHS	Tactile Switches		C455280	https://jlcpcb.com/partdetail/XUNPU-TS_1088R02026/C455280	Extended	6	6 JLCPCB	0.3792
U1	Package_SO:SOIC-16_3.9x9.9mm_P1.27mm	CH552G		Select by System	CH552G	WCH(Jiangsu Qin Heng)	SOP-16	16KB 24MHz 3.3V~5V 51 Family 8bit FLASH SOP-16 Microcontrollers (MCU/MPU/SOC) ROHS	Microcontrollers (MCU/MPU/SOC)		C111292	https://jlcpcb.com/partdetail/WCH_Jiangsu_Qin_Heng-CH552G/C111292	Extended	2	2 JLCPCB	1.3646
<img width="3588" height="254" alt="image" src="https://github.com/user-attachments/assets/c5b94dec-938d-4238-9ab8-06fbcc7e14e2" />

