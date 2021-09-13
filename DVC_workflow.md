# Effect of DVC on Workflows

DVC is a version control system for machine learning projects that is open source. It is a tool that allows you to create your pipeline independent of the programming language you choose. When you discover a bug in an earlier version of your ML model, DVC saves you time by utilizing code data and pipeline versioning to provide repeatability. You can also use DVC pipelines to train your model and share it with your peers. DVC can handle versioning and organizing large volumes of data and storing it in a well-organized, accessible manner. It primarily focuses on data and pipeline versioning and management, although it also has some (limited) experiment tracking features.



- It is possible to utilize many forms of storage—it is storage agnostic.
- Full code and data provenance aid in tracking the whole evolution of an ML model.
- Reproducibility is achieved by consistently retaining a mix of input data, settings, and the code used to perform an experiment.
- Metrics tracking
- A built-in method for connecting ML stages into a DAG and running the entire pipeline end-to-end.
- Keeping track of unsuccessful attempts
- Runs on top of any Git repository and works with any standard Git server or provider.
