# DTU Course 02223 Model-based System Engineering Project

**INSTRUCTIONS FOR RUNNING SIMULATION**

All files that contain the simulations execution have prefix “run_simulation...”. On the top of each file are defined constant values
that can be changes for each run. The parameterized values are:
1. resolution - number of clock ticks per hour,
2. filename_... - path to the file with defined environment.

The simulations runs 10 times and at the end produces two diagrams that are saved in the same directory, the file name
has a resolution number in it as well as indication if it is a energy diagram or an anxiety. Example filename: “en-
ergy_1800_res_compare_systems.png”. One diagram is showing the average energy consumption based on 10 runs and one for
anxiety level. Number of runs can also be changed as well as the file with definition of the environment.

Changing traffic distribution is done by uncommenting a code block in model/time.py.

In order to run the simulation file below command needs to be executed:

python <path_to_run_simulation_file>

where “path_to_run_simulation_file” is path to the file with simulation one wants to run.

Results will be saved in data folder in csv format with the name of scenario and timestamps.

To run an see the GUI, run gui.py.
