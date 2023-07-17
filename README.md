# CCBERT: Self-Supervised Code Change Representation Learning

This is the implementation of "CCBERT: Self-Supervised Code Change Representation Learning" published in the research track in ICSME 2023. 

## Download Replication package
Please download it from this link: https://zenodo.org/record/8153733


## Setup conda environment


```
$ conda create -n ccbert python=3.9
$ conda activate ccbert
$ pip install -r requirements.txt
```

## Downstream tasks
 
 
### JIT Defect prediction

```
$  cd sh
$  bash defect_jdt.sh
$  bash defect_platform.sh
$  bash defect_gerrit.sh
```

### Patch Correctness Assessment

```
$  cd sh
$  bash patch_correctness.sh
```

### Bug-fixing Commit Prediction

```
$  cd sh
$  bash bug_fix_commit.sh
```












