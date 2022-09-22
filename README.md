# SBTCarla: Scenario Based Testing on the CARLA simulator.
This repository is a modified version of the CARLA scenario runner for CARLA 0.9.12 version. The default branch of this repository is nine_twelve to reflect that. 

### Inputs
The goal of SBTCarla is to take multiple modes of inputs to run scenarios in the CARLA simulator:
* Json config files defining sparse details of scenarios. Rest is assumed by SBTCarla
* A list of OpenDrive files
* A list of OpenScenario files.
SBTCarla should have a common interface to take all of these inputs. It should also have the capability to procedurally generate taking in an OpenDrive input. 