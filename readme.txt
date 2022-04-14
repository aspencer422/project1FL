Filename: project1.py

Description:
Program works based off a DFA of 10 states. The program starts with an endless loop prompting user 
for float String input in the main method.  The main method also resets all global variables and 
call the start state of the DFA. The state methods all follow the same template of state actions 
first, then the checks for the next state.  If the state is a final state and the string is done 
the state call a function that builds the final number out of the three numbers possibly build 
from the DFA. If it is not a final state and the string ends, the string gets rejected. 
Also, if a char does not meet the output/input requirements for each state the string is rejected.  
The whole project was done with 10 states.  states q4,q5,q8,q9 are final states, 
while q1,q2,q6 and q7 are not final states.  Q3 was skipped as I found it redundant and decided
 to eliminate it completely.  

State method template:
State(line,i):
# any action for given state
…..
 ….
# if/else checks for correct next state
If(I < line[i]-1)
	If (line[i+1] == ‘.’:
               …. 
                ….
#if final state call final print if last char in string
printFinal()
#end

Github link: https://github.com/aspencer422/project1FL.git

#note: I also included a pdf of my DFA I build to start building my code off of. 
