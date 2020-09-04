To feed the *GUI_environments* you need a list of participants. This list can be generated using the function `scout_bids_for_gui_env`. This function allows you to:

- Get a properly formatted list to feed the `GUI_environments`
- Make a report of *dtseries*, *ptseries* and *dot mat* dot mat files
- Short report showing folders with missing data

To run it, 
```matlab
[T_count, list,text_counts,text_missing] = scout_bids_for_gui_env(root_path)
```