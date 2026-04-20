# Battery_sort
Battery Sort it's a command-line C++ utility for sorting and grouping Li-ion / LiFePO4 battery cells before building a pack. 
You enter the measured capacities of all available cells, choose the pack configuration (e.g. 3S4P), and the program:
filters out outliers (highest and lowest deviations)
groups the remaining cells so each parallel group is as balanced as possible
calculates pack voltage (min / nominal / max) and estimated capacity (Ah and Wh)
optionally saves results to a timestamped .txt file

