---
title: "DPF - Optimal and Fair Decision Trees"
collection: software
category: software
permalink: /software/2022_odt_dpf
excerpt: 'DPF constructs fair and optimal binary classification trees. It minimizes misclassification score, while respecting a demographic parity fairness constraint, for a given size (depth, number of nodes). It can also generate the full Pareto front while optimizing both fairness and accuracy.'
date: 2022-12-31
#venue: 'Advances in NeurIPS-22'
#slidesurl: 'tbd'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2022/file/fe248e22b241ae5a9adf11493c8c12bc-Paper-Conference.pdf'
sourceurl: 'https://gitlab.tudelft.nl/jgmvanderlinde/dpf'
citation: 'Van der Linden, J. G. M., de Weerdt, M. M., & Demirović, E. (2022). &quot;Fair and Optimal Decision Trees: A Dynamic Programming Approach.&quot; <i>Advances in NeurIPS-22</i>, 38899-38911.'
---

The code in this repository implements the DPF algorithm for constructing fair and optimal binary classification trees. It minimizes misclassification score, while respecting a demographic parity fairness constraint, for a given size (depth, number of nodes). It can also generate the full Pareto front while optimizing both fairness and accuracy. 

Based on the MurTree algorithm developed by Emir Demirović et al. ([source](https://bitbucket.org/EmirD/murtree/src/master/)) and its biobjective variant ([source](https://bitbucket.org/EmirD/murtree-bi-objective/src/master/)).

Details about the algorithm can be found in our paper. Please cite our paper if you use our code.

## Compiling
The code can be compiled on Windows or Linux by using cmake. For Windows users, cmake support can be installed as an extension of Visual Studio and then this repository can be imported as a CMake project.

For Linux users, they can use the following commands:

```sh
mkdir build
cd build
cmake ..
cmake --build .
```
This has been tested with gcc 9.4. Older versions may not support the C++17 standard

## Running
After DPF is built, the following command can be used (for example) to find a fair and optimal tree for the Student-Portuguese dataset:
```sh
./DPF -file ../data/student-por-binarized.csv -stat-test-value 0.01 -max-depth 3 -max-num-nodes 7
```

Run the program without any parameters to see a full list of the available parameters.

For benchmarking another program is also built: DPFBenchmark

## Docker
Alternatively, docker can be used to build and run DPF:
```
docker build -t dpf .
docker container run -it dpf /dpf/build/DPF -file /dpf/data/student-por-binarized.csv -stat-test-value 0.01 -max-depth 3 -max-num-nodes 7
```

## Data
The datasets are included in the data folder (except those for which redistribution is not allowed). Source and license information is described per dataset in the data/sources.txt file.



