# Lab 9
For this laboratory I proposed a solution which consists in two different EA strategy:
- Steady State EA
- Generational EA (with Elitism)

I used the "Mutation vs Recombination" approach with 3 different crossover functions:
1. One cut crossover
2. Two cut crossover
3. Uniform crossover

The crossover fuction to be applied is chosen randomly.

## Results
I did some tests to choose the number of generations to use and these are the best results I obtained:

### Steady State EA
|Problem istances|Generations|Fitness calls|Best Fitness|
|:---:|:---:|:---:|:---:|
|1|2500|50050|98.10%|
|2|2500|50050|80.60%|
|5|2500|50050|45.70%|
|10|2500|50050|23.13%|

### Generational EA
|Problem istances|Generations|Fitness calls|Best Fitness|
|:---:|:---:|:---:|:---:|
|1|2500|115128|53.60%|
|2|2500|115089|50.00%|
|5|2500|114930|19.11%|
|10|2500|115116|10.99%|

As you can see from the results with the Generational EA I obained worse results, but this is probably due to some theoretical errors I made in the implementation.