# SER421-Lab2

# Pair: Jonathan Hinkle and Troy Mullins

# Constraints: 
Read in JSON form file(s) at start and read user input from commandline using readline. (I read this to mean he wants us to at least begin the import process before anything else.)

# Functionality shortnotes:
1. Greet user and store name variable. (Does not specify that greeting can't be hard coded)
2. Start conversation with a non-fixed question. (separate dictionary from normal responses.)
3. Parse user input --> Find keywords
(Each keyword pair object should have a number associated with it's rank of importance, response chosen to match highest priority keyword.)
4. Vary responses
	a. Remember responses to a given keyword in a session.
	b. Use Math.random()
5. 20 timeout no reponse ask prompting question.
6. Exit on click
7. Detect new JSON and add to dictionary.
	a. announce "I just got smarter!"
	b. implent through custom EventEmitter.
8. Ever 3 minutes Dunkin message.
9. log command: creates <name>_<Datetime>.log w/ session output.

