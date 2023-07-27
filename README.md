# SeaButtleGame
## There is three versions of Sea Battle. Java basic, kotlin 1 version and kotlin auto.
### The main principles of the algorithm involve placing 1 large ship (4 cells), 2 medium ships (3 cells), 3 basic ships (2 cells), and 4 small ships.
First, we place the large ship (specifying the starting and ending coordinates), then we mark all neighboring cells (within a radius of 1 cell) as the zone for that specific ship. It is prohibited to place other ships in that zone. We repeat this process for all the remaining ships.
The principle of operation of KotlinAuto is that the program randomly places ships on two fields and randomly shoots. Then it determines the winner.
