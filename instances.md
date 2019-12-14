# Instance: Speedboat


name: 'Bullship'  
hasMotor: true  
currentSpeed: 20  
anchorUp: false  
currentDirection: "north"  
crew: ['Captain Ben Dover', 'First Mate Hugh Jass', 'Al Coholic']  

changeDirection (currentDirection = "east")  
isMotorBoat (returns "yes")  
rechristen ('I like big boats and I cannot lie')  
increaseSpeed (20 + 5 = 25)  
raiseAnchor (anchorUp = true)  
lowerAnchor (anchorUp = false)  
walkThePlank (['Captain Ben Dover', 'First Mate Hugh Jass'])  


# Instance: Pirate Ship  


name: "Where's the Booty?'  
hasMotor: false  
currentSpeed: 0  
anchorUp: true  
currentDirection: "east"  
crew: ["Captain Seymour Butts", "First Mate Anita Bath", "Chris P. Bacon"]  

changeDirection (currentDirection = "south")  
isMotorBoat (returns "no")  
rechristen (name = "Unsinkable 2")  
increaseSpeed (0 + 5 = 5)  
raiseAnchor (anchorUp = true)  
lowerAnchor (anchorUp = false)  
walkThePlank (["Captain Seymour Butts", "First Mate Anita Bath"])
