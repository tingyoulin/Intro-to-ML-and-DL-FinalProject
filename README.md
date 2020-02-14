# Intro-to-ML-and-DL-FinalProject
This repositiory is for two Tasks of Final Project of Introduction to ML and DL course.

## Two Tasks
Task 1. Steel Number Detection
<br> Task 2. Damage State Classificaiton

## Task 1
### Dataset
+ Training data: 689 pictures’ names with the number of horizontal rebar, vertical rebar and total rebar.
+ Testing data: 101 pictures’ names and corresponding the number of total rebar.
### Task
Determine the number of rebars in the picture
### Definition of rebar number
+ Label rebar’s surface
+ Label rebars with clear edge
+ Take rebar lap splices(搭接) and bundled rebars(束筋) into account
+ Do not use photos with unrelated objects(hands, feet)
+ Neglect photos with large amounts of missing data

## Task 2
### Dataset
+ Training data: 5000 images with the damage state labels.
+ Testing data: 913 images.
### Task
Determine the damage state (Undamaged/Damaged)

## Grading
+ Milestone (2%)
   * beat early baseline on public leaderboard before 2019/12/11 22:00 (1% + 1%)
+ Baseline (12%):
   * beat the public simple baseline score (1% + 1%)
   * beat the private simple baseline score (1% + 1%)
   * beat the public strong baseline score (2% + 2%)
   * beat the private strong baseline score (2% + 2%)
+ Report (7%)
+ Rank (4%)
   * private leaderboard score ranking (2% + 2%)
