# Overview
 - what it is
 - where to find it
 - credits
# Example

# Exploring the outputs

# Rationale

# Recommended steps in preparation to run it smoothly 

## Explore BIDS folders, get list of participants and report counts

## Pe-calculate variance file for all the subjects

To feed the *GUI_environments* you need a list of participants. This list can be generated using the function `scout_bids_for_gui_env`. This function allows you to:

- Get a properly formatted list to feed the `GUI_environments`
- Make a report of *dtseries*, *ptseries* and *dot mat* dot mat files
- Short report showing folders with missing data

To run it, 
```matlab
[T_count, list,text_counts,text_missing] = scout_bids_for_gui_env(root_path)
```
# Known issues

```matlab
root_path='C:\Users\oscar\Box\CV\ABCD';
[T_count, list,text_counts,text_missing] = scout_bids_for_gui_env(root_path)
%% 
```

# Installation and set-up