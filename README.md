The Repository contains two folders (Cantilever and Simply Supported Beam).

1. Let me explain the naming of the code files
   eg. X_cantilever_with_convergence -> This means a Cantilever beam with a point load at the center
                                        (it can be easily varied just by changing F(desired location) in each code file),
                                        In which X denotes the point load location, which is varied.
                                        Convergence is to tell folks that the code also contains the mean and standard deviation 
                                        convergence with the number of simulations(Monte Carlo Simulations).
2. The code shows a plot of mid-displacement for a simply supported beam and end-displacement for a cantilever beam with
   Histogram and normal distribution.
3. Also, the code shows the convergence of mean and standard deviation with increasing number of runs(Monte Carlo simulations).
4. The terms that are varied in those codes are (flexural rigidity(EI), Point Load(P), Point load location on beam(x),
   and lastly varying all element flexural rigidity along with point load and its location).
5. The meaning of each line in the code is explained in the code itself.
