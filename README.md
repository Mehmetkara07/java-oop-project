# java-oop-project
Outline: In this project, you are expected to write a program that calculates and keeps the tiredness of a rectangular
field as a 2D int array (tirednessMap), given the information about which parts of the field has been planted in the
previous years.
In the first line, the horizontal size of the rectangular field (sizeX) and the vertical size of the rectangular field (sizeY)
will be given as int values. In the second line, a planting information will be given for each previous year as an
information block. The information block will start with the year information (currentYear), how many plantings have
been made during that year (plantingCount) and plant_id s of the plants that have been planted, respectively (all as int
values). In the following plantingCount lines, the planting coordinates of a specific plant will be given as 4 integer
tuples: startXCoord, startYCoord, endXCoord, and endYCoord representing this smaller rectangular area has been
planted in this year. The effect of a plant holds for one year.
Define java class named “Plant” which holds the information of a plant. This class must have three fields:
• plant_id (int)
• plant_name (String)
• tiredness_level (int)
and define one constructor that takes these 3 fields as parameters. Create following 5 objects from this class and then
add all of them to an array named “Plants” whose type is “Plant”.
Plant types and their informations :
plant_id plant_name tiredness_level
1 artichoke 6
2 Tomato 4
3 Wheat 2
4 Corn 3
5 Potato 1
“currentYear, plantingCount, plant_id(s)” line and plantingCount information blocks (start and end coordinates for
each used plant) will continue for each subsequent year until the currentYear’s value becomes 2018, which will be the
last information block.
