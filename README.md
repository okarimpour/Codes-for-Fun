# Codes-for-Fun
Various codes that I just enjoyed

## G. It is all about wisdom
* time limit per test11 seconds
* memory limit per test1024 megabytes
* inputstandard input
* outputstandard output

Foki is the president of the Martian United States of Altanie, Altanie is a very large and strange country. Each citizen in it has a positive integer wisdom value calculated based on her/his age and educational level (of course Foki has the maximum value). Altanie has a big map for all its roads, this map has the following properties:

* There are N cities in Altanie, and the cities are numbered from 1 to N.
* Each road connects 2 different cities, and all roads are bidirectional.
* Each road requires a minimal wisdom value for the citizen to have the right to use it.
* Each road costs some amount of Martian money to use it.
* There is at most one road between each 2 cities.
* Foki cares about all people of his country, so he is wondered about the minimum wisdom value that is needed to go from city * 1 to city N with a total cost less than K, your job is to answer this question for him.

### Input
* The first line of the input contains T the number of the test cases. The first line of each test contains 1 < N ≤ 105 the number of the cities in Altanie, 1 ≤ M ≤ 105, the number of roads connecting the N cities and 1 ≤ K ≤ 109 the total cost.

* Each of the next M lines contain a description of one of the M roads, each road is described with 1 ≤ s1, s2 ≤ N the numbers of two cities the road connects,1 ≤ c ≤ 109 the cost you have to pay each time you use this road, 1 ≤ W ≤ 109the minimal amount of wisdom value needed to have the right to use the road.

### Output
* For each test case print one line contains the answer of the following question: What is the minimum wisdom value a citizen should have to be able to go from city 1 to city N with cost less than K? if there is no solution, print -1.

## References

* https://codeforces.com/gym/100814/problem/G
