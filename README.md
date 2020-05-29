# Metaheuristics Optimization : 
## Part 1 : Discrete Optimization : 
### TSP Problem
National travel sales problems from 
http://www.math.uwaterloo.ca/tsp/world/countries.html#DJ

- In this part, we use the package " satsp " in order to solve the problem .

```
pip install satsp

```
- Algorithm : There are some algorithms can be used for the discrete optimization. ** Simulated Annealing ** is a good choice to be used in this project because of its simplicity in implementation. It shows the good result with short time of calculation. 

 - Set of cities  : 
   ** Djibouti ** 
   38 cities, optimal tour : 6656 
   ** Quatar ** 
   194 cities, optimal tour : 9352 
-  Comments :
   - The parameters used in  simulated annealing are the temperature and the cooling rate (alpha). 
-  Results : 

![Convergence curves](1.2.TSP/qt1.png)

![quartar_path](1.2.TSP/qt2.png)

![Convergence curves](1.2.TSP/dj1.png)

![quartar_path](1.2.TSP/dj2.png)

## Part 2 : Continous Optimization : 
- In this part, we study the 6 classes of shifted functions, three (unmondial functions) have only global minimums and the three others which are the multimondial functions have both local and global minimums. 
- The package used  :
  - Pygmp : ``` pip install pygmo ```
  - Scipy : ``` pip install Scipy ```
- The results are showns in each parts of the folders : 
   - Shifted Sphere : [Result](3.Shifted_Sphere)
   - Schwefel Problem : [Result](4.Schwefel-Problem-2_21)
   - Shifted Rosenbrock :[Result](5.shifted-Rosenbrock)
   - Shifted Rastrigin: [Result](6.shifted-Rastrigin)
   - Shifted Griewand : [Result](7.shifted-Griewand)
   - Shifted Ackley :[Result](8.shifted-Ackley)
