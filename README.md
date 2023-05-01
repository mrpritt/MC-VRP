# An Iterated Tabu Search for the Multi-compartment Vehicle Routing Problem

This respository contains the instances and supplementary data used in Silvestrin, Ritt, [An Iterated Tabu Search for the Multi-compartment Vehicle Routing Problem, Comp. Oper. Res., 81, 192-202, 2017](http://dx.doi.org/10.1016/j.cor.2016.12.023).

## Abstract

 We study a variant of the vehicle routing problem that allows vehicles with multiple compartments. The need for multiple compartments frequently arises in practical applications when there are several products of different quality or type, that must be kept or handled separately. The resulting problem is called the multi-compartment vehicle routing problem (MCVRP). We propose a tabu search heuristic and embed it into a iterated local search to solve the MCVRP. In several experiments we analyze the performance of the iterated tabu search and compare it to results from the literature. We find that it consistently produces solutions that are better than existing heuristic algorithms.

## Supplementary material

* Table 5: Results of the ITS with 103, 104 , 105 and 106 iterations on instances with two compartments and division strategy S1. Split demands are allowed: [10³ iterations](data/2c-1000it.csv), [10⁴ iterations](data/2c-10000it.csv), [10⁵ iterations](data/2c-100000it.csv), [10⁶ iterations](data/2c-1000000it.csv). 
* Table 6: Results of the ITS with 105 iterations and two to five compartments and division strategy S1. Split demands are allowed: [m=2](2-compartment.csv), [m=3](3-compartment.csv), [m=4](4-compartment.csv), [m=5](5-compartment.csv). 
* Table 7: Comparison to the results of El Fallahi et al. (2008), Muyldermans & Pang (2010) and Derigs et al. (2010): the data is the same as in Table 5. 
* Table 8: Comparison to the results of El Fallahi et al. (2008) on instances with division strategy S2: [ITS/Single](data/s2-10000-ws.csv), [ITS/Mult](data/s2-10000.csv).
* Table 9: Comparison of the results of Abdulkader et al. (2015) on instances with division strategy S3 to ITS with single and multiple visits and 104 iterations.: [ITS/Single](data/reed1-10000-ws.csv), [ITS/Multiple](data/reed1-10000.csv). 
* Table 10: Comparison of the results of Abdulkader et al. (2015) on instances with division strategy S4 to ITS with single and multiple visits and 104 iterations: [ITS/Single](data/reed2-10000-ws.csv), [ITS/Multiple](data/reed2-10000.csv). 

## How to cite

```bibtex
@Article{Silvestrin.Ritt/2017,
  author =   {Paulo Vitor Silvestrin and Marcus Ritt},
  title =    {An Iterated Tabu Search for the Multi-compartment Vehicle Routing Problem},
  journal =  {Comp. Oper. Res.}
  year =     {2017},
  volume =   {81},
  pages =    {192--202},
  month =    may,
  doi =      {10.1016/j.cor.2016.12.023}
```
