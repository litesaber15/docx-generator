#Docx Generator

Create multiple word (.docx) files from a template word file that has variables filled in from CSV file.

[Demo](http://cloudproject.c4wmckd9hd.us-west-2.elasticbeanstalk.com/polls/submit)

Sample of word file with variables:
```
[[name]] was a [[role]] in [[series]]. [[pronoun]] was really popular. 
```

Sample of data file (CSV: each line generates a new .docx, each line has values for variables separated by commas):
```
Gandalf the Gray, wizard, Lord of the Rings, He
Hermione, wizard, Harry Potter, She
Groudon, Pokemon, the Pokemon Series, It
```

Sample of mapping: 
```
name, role, series, pronoun
```

Make sure the order of mapping and the order of values in each line of data file is same.
