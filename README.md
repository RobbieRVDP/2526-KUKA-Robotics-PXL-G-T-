These programs were written for a KUKA KR6 R900 sixx Agilus, controlled by a KR C4 smallsize-2.
Files were extracted using WorkVisual6.0.
As for hardware: a forklift scoop was used, combined with 5 pallets that were held in a palletholding rack. Pallets were aligned with eachother, so only the distance in Z-direction was changed.
pallettestDAT was the .dat file for the program, holding locations and variables that were declared outside of the source (.src file).  pallettestSRC was the .src file. holding the program that was used to command the robot.
Some variables might not be found in the .dat nor in the .src, because they were programmed globally into the robot itself. These can be found in configDAT code, which actually is the robot's config.dat- file
Last but not least, hardware changes were also used to change override speed. These were coded into the PLC (or as Germans like to call it: SPS) of the robot, this code can be found int he spsSUB, which is the sps.sub-file.
Code comments were written in Dutch, should you want to translate.

Portfolio branch: Our progress can be read in the portfolio, which was written in a chronological order and displays the struggles, fixes and choices that were made over the course of the project. 

Older versions branch: After every session, code was copied to keep a log. These older versions of the code can be found in the older version branch.

Inspection brancht: An inspection sheet for the robot + controller combination was made for future students to perform regular inspections.
