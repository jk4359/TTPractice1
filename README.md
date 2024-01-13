# TTPractice1

Developed with Unreal Engine 5

Players (4):
1. P1 ("Interrogator") - Human
2. P2 ("Puppeteer/Civilian") - Computer
3. P3 ("AI") - Computer
4. SYS - Computer

Game Flow
1. P2 randomly selects 10 characters from english alphabet
2. P2 generates 5 arrays, each with 5 random characters out of the selected characters
3. AI generates 5 arrays, each with 5 random characters out of the english alphabet
4. SYS randomly picks an array from either P2 or P3 and displays it to P1
5. P1 makes decision (P2 or P3)
6. if P1's decision is correct (ex. selected P2 for P2's array), mark score as correct / if incorrect (ex. selected P2 for P3's array), mark as incorrect.
7. repeat 4-6 until P1 is incorrect 3 times in a row
8. Game-over Screen: Display number of decisions made by P1 & P2's selection of 10 characters.