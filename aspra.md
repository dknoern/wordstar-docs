<pre>
                           DESCRIPTION 



A solar powered aircraft capable of autonomous flights of up to 

one year in endurance will be designed.  The aircraft will be 

equipped with solar cells to power an electric motor and charge 

batteries during the sunlit hours.  The batteries will power the 

engine during darkness.  The aircraft will cruise at 

approximately fifty thousand feet, above clouds and turbulence.  

Only the most necessary instruments will be used.  Navigation 

will be accomplished using a two channel Global Positioning 

System receiver.  An onboard microcomputer will determine course 

and handle all controls.  Although the aircraft will be 

autonomous, a radio data link to the ground-based control station 

will be maintained.  A simple instrument such as carbon dioxide 

or pollution level sensor will also be on board.  The wingspan 

will be in the neighborhood of 100 feet.


</pre>
<pre>

                           BACKGROUND 



Ever since Paul MacCready stunned the world in 1980 with his 

Solar Challenger, the first manned solar-powered aircraft to 

cross the English Channel, great attention has been paid to the 

future of practical solar flight.  Several major aerospace 

corporations have expressed interest in developing giant unmanned 

aircraft capable of flying a year or more high in the atmosphere 

on nothing more than energy from the sun.  Applications for such 

vehicles are numerous - ozone, pollution, and carbon dioxide 

level monitoring of the atmosphere, aerial photography, 

monitoring of drug smuggling activity, observation of whale 

migration, television and cellular phone relays, to name just a 

few.  In short, anything that can be done by a satellite could be 

done at a fraction of the cost and anything that can be done by 

an airplane can be done continuously for an unprecedented length 

of time. 




</pre>
<pre>

                          PROJECT GOAL 



After working full time throughout the summer and at least five 

hrs/week the following school year, I will have the 

configurations, size, and rough structural design determined for 

an aircraft capable of a one-year flight equipped with all 

necessary avionics, radio data link, microcomputer control, and a 

useful atmospheric monitoring instrument.  A working prototype 

proposed by Lockheed has an estimated wingspan in excess of three 

hundred feet and will  cost millions of dollars to produce. My 

goal is to design the plane to be as small, light, simple, and 

cost-effective as possible, an aircraft that could conceivable be 

built (given further refinement) by a small experimental firm or 

university.  It must be stressed that nothing will actually be 

purchased or built.  All aerodynamic components and aspects will 

be designed and tested by a series of computer simulation 

routines.  




</pre>
<pre>

                           POWER TRAIN 



All energy to power the aircraft will be collected by solar cells 

covering the entire upper surface of the wing.  Electricity from 

the cells will power the motor and charge the batteries during 

the day.  The batteries will power the motor during the hours of 

darkness.  The power train needs to be designed to operate at the 

winter solstice (the worst-possible case) when only eight hours 

of sunlight will be available and the batteries must provide 

stored energy for sixteen hours.  The solar array will consist of 

polycrystalline or gallium arsenide cells.  The batteries will 

be either NiCad or water-hydrogen-oxygen fuel cells.  The motor 

used will most likely be a GM Research Labs Magnequench which is 

approximately 92 percent efficient. 




</pre>
<pre>

                            AVIONICS 



Autonomous flight requires avionics of extremely high reliability 

whereas the strict weight constraints of solar-powered flight 

demand a relatively meager set of components.  The heart of the 

avionics system will be a Rockwell International Global 

Positioning System (GPS) unit.  The GPS unit utilizes signals 

from an orbiting array of satellites to determine altitude, 

longitude and latitude with an accuracy of ten meters, twenty-

four hours a day anywhere on or above the earth.  Other necessary 

avionics will include a simple electronic compass and gyroscope 

unit.  A simple on-board microcomputer will coordinate all 

navigation and control information.  A radio communication link 

will also be included to provide position information  and allow 

for course updates.  To provide the aircraft with a useful 

function, a small carbon-dioxide level meter, thermometer, and 

barometer will be included.  A set of electric servos will 

provide control. 




</pre>
<pre>

                         BASIC STRUCTURE 



The basic structure will be independent of size and will be 

determined before the design loop (fig.1) is implemented.  The 

aircraft will be essentially a large wing covered with solar 

cells.  The motor and avionics will be contained either in the 

wing itself (contributing no parasite drag) or in the fuselage.  

The small fuselage will connect the wing body to the tail and 

control surfaces.  The airframe will be constructed primarily of 

carbon fiber tubes for spars and graphite-paper honeycomb for 

wing ribs.  Some sort of light-weight composite will be used for 

the leading and trailing edges.  The airframe will be covered 

with Mylar plastic film.  Unlike the wing on MacCready's Gossamer 

Albatross, that consisted basically of one large carbon fiber tube 

passing through the center of the wing ribs, my design will 

consist of five or so small tubes attached to the perimeter of 

the ribs allowing for a higher strength to weight ratio.    Since 

the goal of my research is to specify the configurations and 

minimum size of a continuous flight solar aircraft, I will not go 

into great detail when determining airframe design.  Only weight 

and bending strength are of major concern. 




</pre>
<pre>

                         DESIGN OUTLINE 


1) The first step will be to contact various manufacturers for 

specifications of solar cells, batteries or fuel cells, motors, 

propellers, and all required avionics.  Information will need to 

be collected regarding weight and power requirements.  


2) Next, the basic airframe structure needs to be determined.  

This will be kept as simple as possible.  Strength is not a 

concern here.  Once in the design algorithm, strength will be 

increased by simply increasing the cross-sectional area of the 

spars. 


3) As an initial guess, an obviously too-small wing area will be 

picked (say 100 square feet).  The wing size and corresponding 

solar array area as well as all fixed weight components 

constitute the input into the design loop.


4) The finite element program is then invoked repeatedly in a 

loop to determine minimum wing strength (and thus weight) 

necessary.


5) Given the wing size, approximate values can easily be obtained 

for vertical and horizontal tail volumes.  Total aircraft weight 

and CG can then be determined.


6) Once the airframe size and shape have been determined, a CFD 

routine is used to determine the aircraft's aerodynamic 

properties.


7) A performance module will then be used to determine power 

required and any other performance characteristics.

8) The power train module will, given wing area, compute power 

use and storage throughout the day and night of the winter 

solstice taking into account the varying angle of the sun. 


9) At this point it is a simple matter to determine whether or 

not the power plant is sufficient to sustain flight throughout 

the winter solstice.  If it is, a feasible design has been 

reached, if not, the wing area will be increased by some 

incremental amount (say 25 square feet) and the design loop will 

be run again. 


ANSYS and VSAERO, or their equivalents will be used for the 

finite element and CFD programs respectively.  I will need to 

write my own code for the performance and power train simulation 

modules.


Once a feasible design has been determined, the major thrust of 

the project is complete, however, time allowing, further work can 

be done.  The structure may be further considered and refined, 

leading to more weight reductions.  Design modifications such as 

dihedral and wing sweeping will be examined to increase stability 

and performance. 

The final design will be one that might exist given present 

technology, however, I will explore further enhancements to the 

design assuming the existence of developments such as higher 

efficiency solar cells (like 3M's new amorphous films to be 

developed here at ISU) and super-conducting engines (a substance 

which superconducts at 390 R, the standard atmosphere temperature 

for 35 - 75 thousand feet, may very well exist within ten years).


                            EQUIPMENT 



Since nothing will actually be built, equipment costs will be 

very low.  I will need an Apollo account and a small budget for 

letters and phone calls to manufacturers.












                       RELEVANT EXPERIENCE 



I spent the summers of 1986 and 1987 as a Engineering 

Intern for Rockwell International, Collins Government Avionics 

Division.  I spent a good deal of time researching various 

manufacturers inquiring about components and casting and plating 

processes.  This experience will certainly aid and speed me in my 

research of solar cells, motors, and avionics.  Also while at 

Rockwell, I completed several small design projects such as 

the design of avionics hardware components and environmental 

testing apparatus.





</pre>
<pre>

                            BENEFITS 



Honestly, I can think of no other project with the potential to 

teach me as much as this one.  The design of an aircraft is a 

synthesized project involving aerodynamics, structures, 

performance, propulsion, and design.  The skills I've obtained in 

Aer E 341, 321, 242, and 361 will all be put to the test.  This 

does not mean, however, that the project is too ambitious or 

overwhelming.  The theory necessary in each of these areas is 

fairly basic, the real challenge will be the actual synthesis of 

disciplines into an elegant series of design steps to arrive at 

the final specifications.  As Paul MacCready showed with his 

Gossamer series aircraft, simple theory coupled with fresh and 

inventive insight can often result in amazing advancements in the 

aerospace field.  Since no one has yet built a solar-powered 

high-endurance aircraft, this project has the added appeal and 

excitement of being a new idea and would provide me with a 

definite feeling of accomplishment.  In light of plans to begin 

development of 3M's amorphous solar films here in Ames, future 

research into solar-powered flight could do a great deal to 

promote the Aerospace Department at Iowa State. 


</pre>
<pre>

                          TIME SCHEDULE




May  31 - Begin work

          Research solar cells, batteries, avionics

June 13 - Design basic airframe structure and decide on materials

June 27 - Work on integrating finite element and CFD routines 

          into design loop.

July 11 - Create power train analysis program

July 18 - Write performance analysis program

August 1 - Run design loop, obtaining feasible design



Fall '88 - Make any necessary modifications in design proceedure 

          and run through again; verify rough design; begin 

          working on design refinements. 



Spring 89' - Continue design refinements; if time permits, look 

             into designing a control system; consider effects of 

             high-efficiency solar amorphous films and 

             superconducting motors. 



</pre>
<pre>


                     ADDITIONAL INFORMATION



After receiving my B.S. degree, I will most likely want to go on 
to get my Masters from Iowa State.  As for my area of emphasis, 
I'm not sure yet, It'll probably be in computational fluid 
dynamics.





Project Director - Dr. James or Dr. Tannehill

</pre>
<pre>

                            CONTENTS





DESCRIPTION ........................................... 1

BACKGROUND ............................................ 2

PROJECT GOAL .......................................... 3

POWER TRAIN ........................................... 4

AVIONICS .............................................. 5

BASIC STRUCTURE ....................................... 6

DESIGN OUTLINE ........................................ 7

EQUIPMENT ............................................. 9

RELEVANT EXPERIENCE ................................... 9

BENEFITS ............................................. 10

TIME SCHEDULE ........................................ 11

ADDITIONAL INFORMATION ............................... 12
</pre>