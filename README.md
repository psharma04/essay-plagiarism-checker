# Essay Plagiarism Checker
A simple concpet for a script that takes an essay and checks it for potential plagiarism. 


Concepts:
- Take sentence as input
- Split text into sentences (maybe use full stop as line break?)
- Search Google for exact string
- If results are returned, store line as variable (as well as potential source), +1 to number of flagged lines
- If no results are returned, check next line
- After all lines are checked, print all conflict lines and number of conflict lines

Possible improvements:
- Request tags for topic, subject, etc.
- For flagged lines, check if the source shares any tags with the essay
- Mark tag-matched lines as likely plagiarism, non-tag-matched as possible plagiarism
