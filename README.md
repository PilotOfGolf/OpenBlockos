# OpenBlockos
<h2>Open-source and free block building toy</h2>
<h3>What is this?</h3>
This is an open-source and free block toy form factor. The idea behind this is for things to be free and accessible for all. The parts are designed with people who have less-than-optimal printers. This way, tolerances don't have to be a problem. This is for people who want a "it just works" type of experience with this. 

![An image with some example prints of some of the OpenBlocko parts.](https://raw.githubusercontent.com/PilotOfGolf/OpenBlockos/main/img/IMG_6021.jpg)

<h3>Specifications</h3>
The parts are designed with the following specifications: 

- A 1x1 Blocko is 15mmx15mm. This size is optimal for printing time and detail. 

- The height is 15mm total, with the nub extending 5mm above the ledge. This is centered on every 1x1 hole. This may need to change. but the base plate may also account for XY tolerances being low. 

- Tolerances are ideally .175mm in all three dimensions. This is to allow users who have lower-end printers to be able to print the Blockos.  This can certainly be subject to change, and very well could, however, this is good enough from my (albeit limited) testing.

<h3>What printer should I use?</h3>
If you want to try printing this on your own, the BambuLab A1 Mini is good for new people, who simply want to print. It is super turnkey and has okay tolerances out of the box. If you are like me and want something you can mod, build a Voron ;)

<h3>How to print the parts?</h3>
Ideally, you should print the parts with a .2mm layer height, at least 2 walls, 3 bottom layers, and 3 top layers. Infill doesn't matter too much, so keep this in mind so you don't waste filament. Don't mess with the novelty settings, as the parts aren't designed with those in mind, which could affect tolerances. 

Material-wise, this is interesting. I would recommend PETG to be safe, however, PLA will work. I would avoid using filaments with abrasives in them (GF, CF, Glow in the Dark, et. al.) as they could mess with how the Blockos fit by adding more friction. A famous block company uses ABS for their parts, however, they are also injection molded, therefore it is a little different. 

Your printer <b>DOES</b> need to be tuned to print well. While you can use a lower-end printer, it still has to be tuned well for everything to work well. I am speaking from experience when I say this: tuning is important, not just for this, but any print where tolerances are tight at all. 

<h3>Who is this for?</h3>
On a more serious note, this project is supposed to bring fun 3D printing to a wider audience. The idea is to bring printing to younger children who enjoy playing with similar block toys, but allow them the opportunity for it to be:
* More personalized, as parts can be made in minutes whatever desired color, and have endless possibilities for physical Blocko personalizations. 
* More educational, as doing this will bring additive manufacturing to younger kids, ultimately teaching them more than what they would have known (even if it is something as simple as how to load filament). 
With that said, this platform can be used by anyone. Many grown adults are fans of a certain block company, this could allow them to learn more about designing their own Blockos, or about additive manufacturing. 

<h3>What is the plan?</h3>
The current focus right now is just putting out the files for as many Blockos as possible. Later down the line, the goal will be to add more customization-oriented things. My goal is to get a library of mainstream parts, which can be used fairly simply. Then once this is complete (or a large amount of parts available, as it won't ever really be "complete" ;) ), I plan to build some software that will make customization easier. This means that you eventually won't have to open CAD if you want to change something about one of the parts. I for sure still think that learning at least the very basics of CAD is important, and you should give it a shot. 

<h3>About the File Directory</h3>
This repo has a rather complex file tree, but it makes sense in my mind, especially once I get more parts designed and things become more convoluted. 

In essence, F3D and STL files are split from the very beginning. Their respective 'child' branches are exact duplicates in terms of their structure, and the only difference is the STL folder has the STL files and the F3D folder has the F3D files. I chose to upload F3D files as opposed to STEP files as this will make it a bit easier for people using Fusion, which is a common 'real' CAD that people use (and the one I use). 

From the F3D/STL folder, the folders will be pretty descriptive, (ie 1x, 2x, baseplates, etc). If they aren't clear to you, you can go to the STL version of the folder and view the files, since GitHub has a built-in STL viewer. 

<h3>Final Thoughts</h3>
This is a passion project, so there are no guarantees anything will work. I am doing this out of my passion for CAD, printing, and to educate people about the former. 
