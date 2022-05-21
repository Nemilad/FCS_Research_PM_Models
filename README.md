# Process mining models of FCS student academic trajectories
Repository contains obtained process mining models with academic trajectories for the students of the Faculty of Computer Science. Models are present in Directly-Follows Graph form and was acquired  with the help of Fluxicon Disco tool.  
The models are used in the Master Thesis.

## File names interpretation
Naming of the images provide information about year, analysis type, module, the course, outcome, filters settings.  

##### Example:
    1_full_4alg_retake_fail_35_2

Each name starts with the year number.  
If the model represents specific paths, it will contain analysis type, module, the course and the outcome of the path.  
Analysis types:
* full - analysis of the most frequent events.
* d - analysis of deviation paths.
* df - analysis of frequent (more than 1 case) deviation paths.
  
Course name caption comes with a module number before the name.  
In case of non-exam event, for example retake, it is specified in the file name.  
The outcome could be the pass or fail.  
If model was filtered by activities or paths filters in Disco, the name will contain the percentage set for these filters.  
Exception for those name structure will be the models containing academic dropouts or ideal path.
