# Working with large datasets

The DVC file defines the data file as well as the instructions that will be run. DVC allows you to quickly save data on a variety of storage systems, including local drives, SSH servers, and cloud services (S3, GCP, etc.). DVC-managed data may be readily shared with other users of this storage system.

#### DVC can precisely record the time and files utilized.

DVC's core is data storage (DVC cache), which is designed for storing and versioning big files. The team can decide which files should be saved in SCM (such as Git) and which should be stored in DVC. Store DVC-managed files in a way that allows DVC to keep several versions of each file and use file system links to easily alter the file version in use.

#### DVC remembers the precise sequence of instructions that were used at a given moment in time.

DVC files can remember not only the files that were utilized in a given execution stage, but also the commands that were performed during that stage. As a result, the produced DVC file contains all of our input data, code and configuration, and output data, which matches to the DVC file presented in the previous section.

#### DVC makes it simple for team members to exchange data and code.

The notion of remote storage exists in DVC. The DVC workspace may send data to and receive data from distant storage. The remote storage pool can be located on any cloud storage platform (S3, GCP, and so on) as well as an SSH server. To share code, settings, and data with coworkers, you must first create a remote storage pool. The SCM keeps track of the configuration file that stores the remote storage definition. Then, copy the SCM repository to the shared server, which includes the DVC configuration file. When your colleagues clone the repository, they will be able to access data from the remote cache right away. This implies that your coworkers won't have to worry about how to run your code. They can quickly replicate your exact processes and achieve outcomes by making full use of reliable data.
