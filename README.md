# Table Header Detection

This repository consists of three directories:
- data: includes our labeled web tables
- notebooks: includes three jupyter notebooks
  - Table Header Detection (This is the main notebook and contains the AdelSam and Improved AdelSam approaches)
  - Random Forests (contains the Simplified approach)
  - Evaluation (contains additional more in-depth methods that we used for our evaluation)
- labeling tool: the tool we used to tag our labels, which is based on Node/Express/Mongo and Pug.js

In order to run our algorithms you need to have a MongoDB instance running. The db name we used is `bob`. The name, however, can be changed in the configurations of each project.

[Download the report](https://github.com/deeps96/web-tables-header-detection/blob/master/Processing%20Web%20Tables.pdf)
