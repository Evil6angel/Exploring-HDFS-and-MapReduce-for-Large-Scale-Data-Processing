# Exploring-HDFS-and-MapReduce-for-Large-Scale-Data-Processing
# Big Data Processing with Hadoop and MapReduce

## Overview
This project demonstrates my hands-on experience with **Hadoop**, **HDFS**, and **MapReduce** for processing large-scale datasets. Using the **Cloudera VM**, I performed the following tasks:
1. **File Manipulation in HDFS**: Uploaded and managed files in Hadoop Distributed File System (HDFS).
2. **MapReduce Programs**: Ran pre-built MapReduce programs (`wordcount` and `wordmean`) to analyze a text dataset.
3. **Custom Python Script**: Developed a Python script to perform word count analysis.

This project highlights working with Big Data tools and frameworks to extract meaningful insights from large datasets.

## Tools & Technologies
- **Hadoop Ecosystem**: HDFS, MapReduce
- **Cloudera VM**
- **Python** (for custom word count program)
- **Terminal Commands** (for file manipulation and running Hadoop jobs)

## Steps
### 1. Setting Up the Environment
- Launched the **Cloudera VM** and ensured all services were running smoothly.

### 2. File Manipulation in HDFS
1. Downloaded a text dataset (Shakespeare's works) and renamed it for personalization.
2. Uploaded the file from the local file system to **HDFS**.
3. Verified the file was successfully stored in HDFS.

### 3. Running MapReduce Programs
1. Explored the pre-built MapReduce programs in the Cloudera VM:
   - Identified input/output formats, number of mappers/reducers, and the Java code for map/reduce functions.
2. Ran the `wordcount` program on the dataset:
   - Saved the results in a designated folder.
   - Highlighted the count for specific words (e.g., "love").
3. Ran the `wordmean` program and analyzed the results.
4. Copied the output files from HDFS to the local file system for further analysis.

### 4. Custom Python Word Count Program
- Developed a Python script to perform word count analysis on the dataset.
- Demonstrated how to run the script in the Cloudera VM environment.

## Video Tutorial
Watch the [video tutorial](video/project_tutorial.mp4) for a step-by-step walkthrough of the project.

## How to Run the Code
1. Launch the Cloudera VM.
2. Use the terminal to navigate to the project directory.
3. Run the Hadoop commands as described in the video.

## Dataset
- The dataset used is the [Shakespeare text file](data/shakespeare).

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
