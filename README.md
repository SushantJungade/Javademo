# eatingMonsterGame
Eating monsters, rules: 
- There are 5 monsters, each monster having 5 calories to start with. 
- Each monster is served a packet of food per round 
- The food packet contains everything from 0 to 2 calories 
- Each monster waits some random time before starting to eat their food 
- When the food is eaten by a monster, it's number of calories will increase with the number of calories contained in the food packet 
- A monster will burn one calorie each time it eats - Statistically, every 5th packet of food is poisoned 
- If a monster eats a poisoned packet of food, it will loose that number of calories - All monsters must finish eating before the next round of servings 
- The strongest monsters eats statistically first, the time to wait from they are served their food is calculated from how many calories they have in them. 
- One monster will also steal food from another random monster per round of serving. It is the first monster waking up that will steal from the others. This is done before it will eat its own packet of food.
- If either the monsters food or the stolen food, the combimed food packet will also be poisoned. 
- A monster is dead if it no longer has any calories, and it will no longer be a participant in the food fight
