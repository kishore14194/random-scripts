Chef Gusteau is one of the finest chefs in Paris. 
Let's understand how he cooks! 

Chef's Ingredients 
1 . The chef receives exactly 1 ingredient per day from the market. The ingredients never repeat. 
2. Every ingredient belongs to 1 of the 3 categories namely FIBER, FAT & CARB. 
3. Every ingredient has a unique ingredient id. 
4. The ingredient id always starts with the category name (ex: FIBERBroccoIi, FATCheese, CARBRice) 

Chef's Dishes 
1 . All of the chefs dishes have a constant number of ingredients. (This will be your program's input) 
2. All the ingredients used will be fully used in a dish. The chef doesn't use some part/quantity of an ingredient. 
3. All of the chefs dishes must have at least 60% of the ingredients from a single category. (i.e. if the chef cooks using 4 ingredients, then at least 3 FAT ingredients OR at least 3 FIBER ingredients OR at least 3 CARB ingredients are needed) 

Chef's Cooking Style 
1 . If the chef has multiple options of ingredients for the dish, then he takes the oldest possible ones to cook in the order of their arrival. 
2. After the chef prepares a dish, the ingredients used can NOT be re-used as they've been already used. 
3. The chef prepares a maximum of 1 dish per day. 
4. If the chef doesn't have enough ingredients to cook the dish with above- mentioned rules, then he doesn't cook on that day. 

Given the input array of ingredient id that the chef receives every day (i.e.array index is the day number) write a program to print when does the chef cook a dish and when he doesn't. 

INPUT: 
Line 1: The total number of days for the scope of the problem (1 <= input <= 20) 
Line 2: The exact number of ingredients that chef uses to cook (1 <= input <= 20) 
Line 3: The space separated ingredient ids. (6 <= length(ingredientld) <= 20) 
OUTPUT: Print the separated used ingredient ids in order of their arrival if the chef cooks on that day and print "-" if the chef doesn't cook anything on that day. 

Print the output as a single string. 

NOTE: Please focus on submitting a working solution.

We are not looking for optimization in this round. 
Please feel comfortable to use brute-force.