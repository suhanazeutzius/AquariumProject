# AquariumProject

How to run: java FishTank

GUI Controls: 
Feed button will add plankton to the tank (whatever number you enter in the box)

Add Fish/Shark/Jellyfish will add that creature at the health you put in the box next to it

Speed/Metabolism/Deadliness sliders will change that variable for the whole species 

	Speed: 1-5
	Deadliness: 1-3
	Metabolism: 1-10 (1 will lose a health every 5 seconds, 10 will lose a health every ~1 sec)
	Health: can be set to any positive number but if negative will give error message and not make a creature
Pause will stop all movement but you can still add/click on creatures regardless of pause status 
If you click on a creature it will display that creatures stats in the information boxes 

Behaviors:  
  Plankton: are dropped in from the top of the screen and sink a random amount  
  Fish: swim across the screen and eat plankton, go up and down a little  
  Sharks: swim diagonally and eat fish and jellyfish  
  Jellyfish: float where they are and may sting sharks and fish (have a higher chance of stinging the sharks and fish if the deadliness is set to a higher level; if it's 1, there a 1/3 chance the fish will die and 1/12 chance the sharks will die; if it's 3 then the fish will almost definitely die and the sharks only have a 1/4 chance of survival)

Other:
when anything dies it floats to the top (dies at 0 health or when the jellyfish does a lethal sting)

