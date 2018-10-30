# KBAI-visual-agent

## Purpose 
Artificial intelligence agent that uses a visual method to solve Raven's Progressive Matrices (2x2 and 3x3) human intelligence tests. Agent employs weighted voting to select an answer or skip a question. Completed for Georgia Tech OMSCS CS 7637

##Requirements
* Python 3
* NumPy
* Pillow

## Running the Agent
Before running, configure which RPM sets to test against in ````Problems\ProblemSetList```` by adding or removing sets.

From command line:
````python RavensProject.py````

## Viewing Results
Results are available in ````AgentAnswers.csv```` and ````ProblemResults.csv````

## Raven's Progressive Matrices Source
RPMs under test are located in the ````Problems```` directory.

## Misc
Code in Agent.py written by me. All other code supplied by OMSCS CS 7637.

Agent performs well on Basic sets B and E, more work needed to have uniform performance on Basic sets C and D. Current stats:
* Basic B: 9/12
* Basic C: 7/12
* Basic D: 6/12
* Basic E: 10/12
