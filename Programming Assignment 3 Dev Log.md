\---  
\#\#\# Entry 1  
\*\*Date:\*\* 2026-04-29  
\*\*Entry Type:\*\* Engineering Decision  
\*\*Task worked on: Implementing function variables for dfs and adding some returns\*\*  
\*\*Issue or decision: Adding variables based on summary list\*\*  
\*\*Error message / symptom (if applicable): N/A\*\*  
\*\*What I tried: I tried to implement the variables for the function and added some returns based on what I believe the dfs needed\*\*  
\*\*Fix / resolution (or final decision): Followed the summary variables listed in the readme document\*\*  
\*\*Commit(s): One commit made\*\*  
\---  
\#\#\# Entry 2  
\*\*Date:\*\* 2026-05-02  
\*\*Entry Type:\*\*Engineering Decision  
\*\*Task worked on: I began to implement the recursive function\*\*  
\*\*Issue or decision: I implemented a for loop that ran from 0 to 4, due to the 4 potential neighbors that a node has\*\*  
\*\*Error message / symptom (if applicable): N/A\*\*  
\*\*What I tried: I tried to add a basic recursive system, not working at the moment, but the skeleton is there\*\*  
\*\*Fix / resolution (or final decision): Basic design, full implementation later\*\*  
\*\*Commit(s): One commit made\*\*  
\---  
\#\#\# Entry 3  
\*\*Date:\*\* 2026-05-03  
\*\*Entry Type:\*\* Bug Fix  
\*\*Task worked on: Bug fix when running the program\*\*  
\*\*Issue or decision: Keep getting an exit code \-1073740791 (0xC0000409) instead of the expected “No paths found”\*\*  
\*\*Error message / symptom (if applicable): \-1073740791 (0xC0000409)\*\*  
\*\*What I tried: I tried modifying and deleting some returns to slowly trace down what was causing the issue to happen\*\*  
\*\*Fix / resolution (or final decision): The solution to the problem was that there were no checks on whether it was dfs out of bounds. So I added a simple check to see if r and c were outside the boundaries of the maze\*\*  
\*\*Commit(s): One commit made\*\*  
\---  
\#\#\# Entry 4  
\*\*Date:\*\* 2026-05-04  
\*\*Entry Type:\*\* Edge Case  
\*\*Task worked on: Worked on setting the parents of nodes and added more checks for the out-of-bounds check\*\*  
\*\*Issue or decision: Implemented the parents for r and c that way the program would be able to later on print out the path used to reach the exit from the start. I also added a check to see if r and c were greater than the maze size, since it occasionally produces an error\*\*  
\*\*Error message / symptom (if applicable): N/A\*\*  
\*\*What I tried: I added the parents into the recursive function\*\*  
\*\*Fix / resolution (or final decision): Implemented the parents and added additional checks to address out-of-bounds errors\*\*  
\*\*Commit(s): Twocommit made\*\*  
\---  
\#\#\# Entry 5  
\*\*Date:\*\* 2026-05-06  
\*\*Entry Type:\*\* Bug Fix  
\*\*Task worked on: Moved the parents outside of the recursive function\*\*  
\*\*Issue or decision: Moved the parents since I reread the readme document, and saw that they were supposed to be assigned before recursing. One issue I’m facing is that after 3 trial runs with varying maze sizes, the program would stop and run indefinitely without providing a solution\*\*  
\*\*Error message / symptom (if applicable): N/A\*\*  
\*\*What I tried: I reread the readme document to see what else needs to be done. As for the bug, no solution has been found since no error codes are given\*\*  
\*\*Fix / resolution (or final decision): Moved parents, and the bug is still unaddressed\*\*  
\*\*Commit(s): Two commits made\*\*  
\---