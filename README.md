# Google Hash Code 2021 Practice
# Authors
- Nikhil Razdan
- Harshit Joshi
# Greedy Solution
## Algorithm
- alg solution: O(m^2 * n)
- start with random team with largest size
- find best set of pizzas for that team
  - from first pizza:
  - if pizza is all unique ingredients, take it
  - if not, assign value to index (dictionary)
  - if no unique pizza found, add best to pizzas
  - repeat for all pizzas
- move on to next biggest team
- repeat until all teams done

# Score
- A – Example: 49 points
- B – A little bit of everything: 6,972 points
- C – Many ingredients: 349,095,013 points
- D – Many pizzas: 6,032,931 points
- E – Many teams: 10,902,031 points
