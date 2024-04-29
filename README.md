# Protest noise makers

Simple 3D printable noise makers. Use for fighting colonialism, fascism and unfair labor practices. 

Developed during the UCLA Graduate strike of 2022.

![](/guidePhotos/NOISE_-12.jpg)

## 3D printable files

Ready to print .stl files are located in the [3DprintFiles](3DprintFiles) directory. 

There are two models: 
- [NoiseMakerSimple.stl](3DprintFiles/NoiseMakerSimple.stl) is a single chamber model. Easiest and quickest to print. 
- [NoiseMakerTriple.stl](3DprintFiles/NoiseMakerTriple.stl) is a triple chamber model. Much louder and creates a poly tonal sound. Uses much more material to print. 


## Assembly guide

A video of the assembly process can be found [here](https://youtu.be/jMzxnDv2O78)

#### Step 1 - Print a noise maker body
These devices are printed as a single piece. 
Some notes on the printing process:
- all tests have been made with PLA
- prints have been tested up to .28 mm layer height. They should work up to .4 mm
- the mouthpiece will need supports. Make sure to not include supports inside the chambers or it may be difficult to remove
- an infill of about 15% is more than enough

#### Step 2 - Gather materials
To build a noise maker, you will need:
- a 3D printed noise maker body (using the single chamber model for this guide)
- some sandpaper (something like 150 grit works well)
- a pair of scissors
- a rubber band
- a nitrile glove (latex gloves, balloons, or plastic bags can also be used. Different materials will produce different timbres) 

![](/guidePhotos/NOISE_-01.jpg)

#### Step 3 - Remove supports from 3D printed body
 
![](/guidePhotos/NOISE_-02.jpg)

![](/guidePhotos/NOISE_-03.jpg)

#### Step 4 - Sand the upper end of the body, until there are no sharp irregularities

![](/guidePhotos/NOISE_-04.jpg)

![](/guidePhotos/NOISE_-05.jpg)

![](/guidePhotos/NOISE_-06.jpg)

#### Step 5 -  Cut a square of material from the glove. It needs to be bigger than the diameter of the body. This will act as the vibrating membrane.

![](/guidePhotos/NOISE_-07.jpg)

![](/guidePhotos/NOISE_-08.jpg)

#### Step 6 - Stretch the membrane over the sanded end

![](/guidePhotos/NOISE_-09.jpg)

#### Step 7 - Secure the membrane with the rubber band. Make sure it's tight and that there are no creases.

![](/guidePhotos/NOISE_-10.jpg)

![](/guidePhotos/NOISE_-11.jpg)

### Done!

## Tests

https://github.com/auzal/noise_makers/assets/3940167/49ffc315-b2f3-4ef4-8d3e-ae68fc700136

Testing the single chamber version

https://github.com/auzal/noise_makers/assets/3940167/70f62b58-36f9-45e0-9690-6776add53538

Testing the triple chamber version

## Design

![](/guidePhotos/noise-makers.png)

These devices work by blowing air through the mouthpiece. The air is then forced through an elastic membrane, which vibrates and pushes the air out of the inner tube, creating a loud sound. 

![](/guidePhotos/cross_section.png)
Cross section view of both devices

These devices were modeled in Fusion 360. The design files can be found in the [fusionFiles](fusionFiles) directory. 

Some notes on the Fusion files:
- the design is parametric, so dimensions are easy to change
- changing the diameter of the chambers will affect the amplitude of the sound
- changing the length of the inner tube will affect the pitch (shorter tube means higher pitch)
- on the triple chamber design, the length of each inner tube can be adjusted individually

