# Evalution of CovExitAug
This repository contains the generality evaluation of CovExitAug.
The soundness issue evalution of CovExitAug is in repository [deb-soundnessIssue](https://github.com/the-Soundness-of-Debloating/deb-soundnessIssue).

## Evaluation Results
File "evalution_output.txt" contains the output of the evaluation script.
The evaluation results can be found here.

## Evaluation Data
Folder "generality_evaluation" contains the raw data of the evaluation.

For every program "program_name" in ChiselBench, there is a folder named "[program_name]_evaluation" which contains the evaluation result of the program, and three source codes of the program, "[program_name]-[version].c.origin.c", "[program_name]-[version].c.reduced.c", and "[program_name]-[version].c.reduced.augmented.c", which are the original program, the Cov-debloated program, and the CovExitAug-debloated program, respectively.

In the "[program_name]_evaluation" subfolder, "dir_original", "dir1", and "dir2" store the output of the original program, the Cov-debloated program, and the CovExitAug-debloated program, respectively, when running the program with the generality testing inputs.
