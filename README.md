# circuitsimulator

Optimization of the sub-optimal electrical circuit simulation is done here by the implementation of a priority queue in place of a highly inefficient(array based) data structure. While the sub-optimal implementation has a time complexity of O(n), the newly optimized implementation allows for insertions and deletions in constant O(1) time. This is done by profiling the said simulator and detecting the methods with high time complexity and replacing them with efficient methods. The built-in python profiler can be used for profiling the simulator.
