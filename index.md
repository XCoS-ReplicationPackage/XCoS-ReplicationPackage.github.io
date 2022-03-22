# Replication Package of XCoS

we conduct a series of experiments to evaluate the quality of the key steps of XCoS and the effectiveness and usefulness of XCoS by answering the following research questions.
* RQ1 (Quality): What is the intrinsic quality of the results of the key steps of XCoS?
* RQ2 (Effectiveness): How effective is XCoS in generating explanations for code search in terms of completeness, conciseness, and readability?
* RQ3 (Usefulness): How useful is XCoS in helping developers during code search tasks?


## RQ1 Quality of Key Steps
We respectively sample 384, 384 and 50 instances to evaluate the quality of **concept identification** and **concept linking for description**, and **concept linking for code**.

The sampled and annotated data can be found in the file [rq1-final]().

## RQ2 Effectiveness for Generating Explanations
We ask 6 participants to evaluate the generated explanations on 10 tasks in terms of completeness, conciseness, and readability on a 4-points Likert scale (1-disagree; 2-somewhat disagree; 3-somewhat agree; 4-agree) by the following statements.
* Completeness. The explanations contain all the necessary information for explaining search results.
* Conciseness. The explanations contain no (or very little) unnecessary or redundant information for explaining search results.
* Readability. The explanations are well-organized and easy to understand.

The tasks and results can be found in Table 2 in our paper.

## RQ3 Usefulness of XCoS
We divide the tasks into two roughly equivalent group TA (Task1, Task3, Task5, Task7, and Task9) and TB (Task2, Task4, Task6, Task8, and Task10). In each group, the number of tasks in easy, medium, hard level are 2, 2, 1 respectively.
We divide 14 participants into two “equivalent” groups GA (A1-A7) and GB (B1-B7) and each group with 2 beginner, 3 intermediate, and 2 advanced.

The evaluation results can be found in the file [rq3-final](./rq3-final.xlsx).
