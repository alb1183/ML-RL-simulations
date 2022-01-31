# ML-RL-simulations
A multi-layer guided reinforcement learning-based tasks offloading in edge computing - Simulations

# Table of contents
- [Metrics](#metrics)
- [Experimental Results and Analysis](#experimental-results-and-analysis)
- [Preview of the simulations](#preview-of-the-simulations)
  - [Greedy algorithm](#greedy-algorithm)
  - [Local Reinforcement Learning algorithm](#local-reinforcement-learning-algorithm)
  - [Multi-Layer Reinforcement Learning algorithm](#multi-layer-reinforcement-learning-algorithm)

# Metrics
In order to compare the performance of each algorithm we have defined the following benchmark metrics:

* **Task Success Rate:** The percentage of the tasks that finish their execution over the total. A task is not considered to complete its execution correctly if its execution time exceeds its deadline or if the offloading process fails. This metric is one of the most important for the evaluation process.
* **Average Total Time:** The total time required to complete successfully a task, which includes the execution time and the time to send the task to the processing node. This metric is especially useful for comparing the latency incurred by each algorithm.
* **Average Real Total Time:** Same as **Average Total Time** but also considering the time wasted on tasks that were not executed successfully.
* **Failed tasks due to latency:** The number of tasks that have failed because their execution time exceeds their maximum allowed latency.
* **Average CPU Usage per device:** Average CPU usage of a device. Useful to determine how much the computational resources of the devices are used.
* **Average Energy Consumption per Device:** Average power consumption of one device. 


# Experimental Results and Analysis

TODO

| Tasks Success Rate | Average Total Time | Average Real Total Time | Failed tasks due to latency | Average CPU Usage per device | Average Energy per Device |
|---|---|---|---|---|---|
| ![TasksSuccessRate](TasksSuccessRate.png) | ![AvgTotalTime](AvgTotalTime.png) | ![AvgRealTotalTime](AvgRealTotalTime.png) | ![AvgRealTotalTime](TasksFailedDueDelay.png) | ![AvgVMCPUUsage](AvgVMCPUUsage.png) | ![AvgEnergyConsumptionPerDevice](AvgEnergyConsumptionPerDevice.png) |
| TODO | TODO | TODO | TODO | TODO | TODO |

TODO

# Preview of the simulations
Examples of some simulations performed for different number of devices and algorithms.

## Greedy algorithm
Example of greedy algorithm with 160 devices and random mobility.

![Greedy](Simulation%20Previews/Greedy_160.gif)

## Local Reinforcement Learning algorithm
Example of local knowledge RL algorithm with 160 devices and random mobility.

![Local](Simulation%20Previews/RL_Local_160.gif)

## Multi-Layer Reinforcement Learning algorithm
Example of the multi-layer extension of the RL algorithm with 160 devices and random mobility.

![MultiLayer](Simulation%20Previews/RL_ML_Empty_160.gif)
