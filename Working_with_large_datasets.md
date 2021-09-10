# Accessing and Preserving Large Datasets before DVC

Controlling large-scale data without DVC or a similar tool is almost inconceivable today. Before these tools evolved, ML statistics were handled manually by good old CTRL-C, CTRL-V, and conventional file trees. Here were a few tactics used to manage unwieldy large data files:

- **Allocate more memory**: One method was to use a tool to increase the available memory for your machine learning libraries.

- **Smaller samples**: DVC enables you to track large data files (from 10 G to 100 GB). Before DVC, however, tracking such large files was not possible, so engineers had to work on portable samples of thousands or hundreds of thousands of rows at a time.

- **Allocate more hardware**: Separate computing machines or cloud services were used to run algorithms so as to avoid crashes.

- **Change data format**: Another approach was to alter your data format from CSV to binary to save large data in a more compact form.

- **Relational databases**: These were used to store and retrieve big datasets in a less taxing fashion.
