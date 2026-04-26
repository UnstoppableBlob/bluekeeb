# Bluekeeb

A custom made low-profile mechanical keyboard that uses a XIAO seeed module as the controller, a master-slave implementation of the firmware, that uses ZMK. Hassles with batteries can be avoided, due to the battery management and charging systems of the XIAO module in use. I have made the decision to remove the row of function keys, and replace them with a rotary encoder on the right side that controls music volume, and on the left side, a rotary encoder that controls the brightness of your display.

## How I made this

I made this using the OPL Kicad Library, running Kicad 8.0 on Windows 11. I have compiled it all to a manufacturable gerbers.zip file containing all the important info. I have a rotary encoder, which I'm planning to use a standard, 11 millimeter ec11 rotary encoder. Along with that, I'm going to use Choc v1 Kailh key switches, paired with custom 3d-printed keycaps. 

## Why did I make this

I made it because I was bored, and then I ended up spending a lot of time on it I guess? Also to qualify for stasis.hackclub.com's hackathon in Austin, TX.

## Assembled PCB (without the case and keycaps)
<img width="1198" height="742" alt="Screenshot 2025-12-18 115908" src="https://github.com/user-attachments/assets/c35d7380-87c0-48a3-a420-20a87573f8b0" />

## PCB
<img width="848" height="823" alt="Screenshot 2025-12-18 115355" src="https://github.com/user-attachments/assets/289e743e-d9ec-41a2-afe1-6a4c6ddf6dfd" />

## Schematic
<img width="1303" height="838" alt="Screenshot 2025-12-18 115051" src="https://github.com/user-attachments/assets/4250d762-e3f9-4b6a-85b5-a5ffbfad4e0c" />

## Case + PCB + electronics

Actually, while I was using freecad, after I had the whole thing set up, It didn't let me export or import files, even though I was trying to import/export supported file formats. I was only able to get the case, rotary encoders, and the PCB to show up on the render. 
![alt text](image.png)

## Case + PCB (older version)
<img width="1424" height="939" alt="image" src="https://github.com/user-attachments/assets/13252680-3234-4b66-b35c-358ec911e8dd" />


The newer case (Bluekeeb case.step, not bluekeeb.step) is a newer version of the case that I am going to print out myself, as well as ordering all the components myself. The cases has a slot open for the usb c cable connection coming from the XIAO module.
