Job Description / Resume Parser
===============================
created by Vineet Jain

This program analyzes text from an input job description or an input resume and generates an output that consists of meaningful sentences as well as hot keywords.

###How to Run

The user can run the program with or without an output file specified. An input file must be specified.

With an output file:
`javac -g Parser.java`
`java Parser.java <input-file> <output-file>`

Without an output file:
`javac -g Parser.java`
`java Parser.java <input-file>`

The user can also add to the system files `keywords.txt` and `verbs.txt` to allow for a more accurate analysis of the program. To do so we can run the AddToFile class

`javac -g AddToFiles.java`
`java AddToFiles`

Then follow the program's prompts.