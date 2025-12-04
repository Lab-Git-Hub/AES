# Data and Results
This repository contains the data of the Yangtze River and experimental results of the paper: 

**A branch-and-price approach for optimizing all-electric ships scheduling in waterborne transport**

## Data

### Instance
* `Benchmark_instances.xlsx`:
  Instance settings used in *Section 7. Numerical experiments*.

### Data for Computational Results (Section 7.2.)

Port26 contains the data for R5–R25, and Port30 contains the data for R30.

*  *port_distances.csv*:
Distance matrix of all ports (arc length of the inland waterway shipping network).

*  *port_segment_dis.csv*:
Sailing distances between all adjacent ports (arc length of the realistic inland waterway topology).

* *port_seq.csv*:
Ports are categorized by type, where Type 1 indicates a port on the main waterway and Type 0 indicates a port on a tributary.

* port_traveltime.csv*:
Flow-dependent sailing time of each arc in the inland waterway shipping network.

### Data for Sensitivity Analysis (Section 7.3.1)

Network data used in *Section 7.3.1 Impact of the network density*.

## Results
Results of *Section 7. Numerical experiments* are provided.

* *Result_BS_mode.xlsx*: results of the three battery swapping strategies baseline, heuristic, and BP used in *Section 7.2.1*.

* **Result_Gurobi&BP.xlsx**: benchmarking results comparing Gurobi and BP across instance scales R5–R30 as reported in *Section 7.2.2*.

* **Result_BP_with_Gurobi_Incum.xlsx**: results comparing BP initialized with Gurobi’s first incumbent versus BP initialized with the construction heuristic in *Section 7.2.3*.

* **Result_Schedules.xlsx**: scheduling solutions for representative instances across scales R5–R30, including ship routes, battery swapping locations, and route costs.

* **Result_sens_density.xlsx**: results of the network density sensitivity analysis presented in *Section 7.3.1*.

* **Result_sens_horizon.xlsx**: results of the planning horizon sensitivity analysis presented in *Section 7.3.2*.



