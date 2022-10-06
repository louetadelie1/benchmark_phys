Only works on PHYS cluster 
Only tests up to 4 nodes
Need the topology file in the directory where you execute the script
Benchmark results will be printed under filename **Benchmark_Perfomance.png** in the same directory where script was executed
Check progress by executing squeue -n bingo in terminal (when no jobs are running, results should be available)



NEED TO LOAD ANACONDA/3/2020.2 ON PHYS CLUSTER PRIOR TO USING LIB

If you download all the code on personal comp (best method)
Execute the following:	
module load anaconda/3/2020.02 
python3
from phys_benchmark import num_nodes
num_nodes("# of nodes you want to test -- 4 nodes max)
exit()

