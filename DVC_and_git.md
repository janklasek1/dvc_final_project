# DVC and Git

Although DVC can run on its own, it usually takes advantage of Git features and runs on top of it. 

For storage of large parts, DVC uses remote repositories such as Google Cloud, S3 or Azure. 

Git is being used as a foundation to track the lifecycle of the model and what command were used to produce metrics. When using .dvc files, it also downloads the relevant Git repository.

If the datasets are small in size, Git is sufficient, for large data files may be stored in remote storages of DVC. Read more about it here.
