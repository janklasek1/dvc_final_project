# Disadvantages of DVC

Although DVC provides an improvement in the efficiency of data science work, several disadvantage loom which one should be wary of: 

#### Redundancy

If the project uses an alternative pipeline tool, this can lead to redundancy as the pipeline management is intrinsically connected to DVC. 

#### Risk of Incorrect Configuration

The pipeline may be incorrectly configured which - for instance, in the event that a team forgets to add an output file. 
In such case, old projects cannot be easily reproduced and may not work in a new set of circumstances. 
Worryingly, debugging and detecting missing dependencies in DVC is challenging. 

#### Architecture Dependent Performance

Metrics and datasets must be properly defined within the framework of the architecture as DVC works in conjunction with Git. 
In the absense of proper definitions, the setup of a version controlling system may not be utilized to the fullest extent. 
Therefore, in order for the machine learning to work, data scientist teams may be required to create in-house additions to DVC for proper functioning.






