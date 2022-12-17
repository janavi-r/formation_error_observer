# formation_error_observer

## To change path in all python files:
Open terminal and navigate to "<workspace>/src/formation_error_observer/"

```
python3 utils.py

```
## To record data published by robots

```
ros2 run formation_error_observer main

```
Press 'ctrl+c' at the end of execution to save the data to Json and CSV

## To plot the coordinates based on data

```
ros2 run formation_error_observer plotter

```

Json and CSV files can be found in "<workspace>/src/formation_error_observer/data" folder