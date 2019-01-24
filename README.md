# CSCI736-Breeds-of-cat-classification (Java program)
For this project, a house cat breed classification expert system has been implemented. Initially, I planned to implement all breeds of cat list in Wiki page. However, due to the working time and the size of this project, I only choice 13 breeds of all as list below.

Design & Implementation
In the program, you will be asked to provide some information about the cat: 
1. The body shape (type) of the cat.
2. The continent of the cat.
3. The coat length of the cat (scale 0-10 cm).
4. If the color of the coat uniform.
5. If the color cover whole body.
6. How many numbers of color does it have?
7. The shape of the color fur.
Based on the selected value, the expert system will fire the rules to get the final breed of the cat you selected.
There are 41 rules in total, and they are divided into 5 different groups. Group 1 will inference coat based on the length of the fur. Group 2 will inference pattern of the coat based on Q4-7. Group 3 will use the pattern get from Group 2 and continent to narrow down the breeds of cat. Group 4 will use the info get from before narrowing down the Country the cat from. Group 5 will find out the breed of the cat. 

Test cases: 	
1. Exotic Shorthair: cobby, NorthAmerica, <0-1, true, true, 1-3, any
2.  Scottish Fold: cobby, Europe, <7-10, any, any, any, any
3. Japanese Bobtail: moderate, Asia, 0-1/<7-10, false, false, 2, “Block”
4. British Shorthair: cobby, Europe, <0-1, any, any, any, any
5.  Persian: cobby, NorthAmerica, <7-10, any, any, any, any
6. Bombay: moderate, NorthAmerica, <0-1, true, true, 1, “Round”
7. Bengal: empty, NorthAmerica, <0-1, true, false, 2, “Round”
8. American Curl: empty, NorthAmerica, <0-1/<7-10, any, any, any, any
9. Norwegian Forest cat: empty, Europe, <7-10, false, false, 2, “Block”
10. Maine Coon: large, NorthAmerica, <7-10, false, false, 2, “Block”
11. Sphynx: oriental, NorthAmerica, 0, any, any, any, any
12. Aegean: empty, Europe, <1-7, true, false, 2/3, “Block”
13. Turkish Angora: empty, Asia, <1-7, false, false, 2, “Block”


