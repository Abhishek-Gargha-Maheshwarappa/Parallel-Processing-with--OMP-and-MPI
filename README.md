# Parallel-Processing-with--OMP-and-MPI
# **Several reasons to use parallel computing**

1.	Save time/money
2.	Solve Larger/More Complex problems like Web search engines/databases processing millions of transactions every second
3.	Provide Concurrency, for example Collaborative Networks provide a global venue where people from around the world can meet and conduct work virtually
4.	Take Advantage of Non – local Resources that is using compute resources on a wide area network, or even the internet when local compute resources are scarce or insufficient
5.	Make better use of Underlying Parallel Hardware

# **Parallel Programming Models**

There are several parallel programming models in common use:
1.  Shared Memory (without threads)
2.  Threads
3.  Distributed Memory / Message Passing
4.  Data Parallel
5.  Hybrid
6.  SPMD and MPMD

# **Amdahl's Law**

It states that potential program speedup is defined by the fraction of code (P) that can be parallelized:

# Speedup = **<img src="https://render.githubusercontent.com/render/math?math=\frac{1}{(1-p)}">**

The number of processors performing the parallel fraction of work, the relationship can be modeled by:

Speedup= **<img src="https://render.githubusercontent.com/render/math?math=\frac{1}{((P/N)+S)}">**

### where 
P = parallel fraction, 

N = number of processors and 

S = serial fraction

These code were tested on [Discovery]<https://rc.northeastern.edu/>

The output 

Format: ![Alt Text](https://github.com/Abhishek-Gargha-Maheshwarappa/Parallel-Processing-with--OMP-and-MPI/blob/main/output_screenshots/Hw1-part2-output.JPG)

Format: ![Alt Text](https://github.com/Abhishek-Gargha-Maheshwarappa/Recommendation-systems/blob/master/matrix.JPG)
Format: ![Alt Text](https://github.com/Abhishek-Gargha-Maheshwarappa/Recommendation-systems/blob/master/matrix.JPG)
