# Advantages of DVC

Data version Control provides data scientists with the ability of managing, storing and, likely most importantly, reusing existing models. 

There several advantages to using DVC: 

#### Ability to share models via Cloud Storage


Cloud servers, such as Microsoft Azure, Amazon S3 and Google SSH, enable the centralised storage of data. 
As such, models are easily avaliable to members of a team while simulaneously being able to run models on a shared machine. 

#### Visualisation and Tracking of ML Models

Data repositories enable the versioning of work in DVC. In this regard, DVC does not fundamentally differ from non-data Git projects. 
However, in order to store ML artifacts, DVC utilises a built-in cache, which subsequently syncronises with a remote cloud server for storage.

#### Reproducibility

DVC allows for data registries to be created which can easily be reproduced and reused. 
Since DVC stores all history, a single commit can provide a reproducable model for another project. 

#### Organised ML Data

Machine leaning requires clean data and cleaning out data structures is often a time consuming task. 
DVC allow for the structure to be replicated and thus organised for easier use in future projects. 







