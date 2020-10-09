# Minilab 06

In project1, we looked at the most common
words in positive reviews with a rating of 9 or 10
and most common words in negative reviews
with a rating of 1 or 2.
We did this by having one or more lines
lines like cat `*_10.txt`.  

What if we needed to repeat this process regularly
for some other potential set of reviews, for instance
just those reviews with rating 1, just those with rating 7,
etc or all reviews in some range?  We can use
a shell script to make this easier.


Today we are going to adapt project 1 to accomplish
this by turning it into a shell script. 
If you didn't finish project1 or don't feel like
working with the whole list of commands, don't worry about
outputting the most common words, just create
your script so it goes as far as 
combining the relevant reviews into a file.

### Task
Write a shell script that
1. Takes as its first argument the path to the higher level
   review directory so a path that includes `train` or
   `test`, but not `pos` or `neg`.
2. Takes as its second argument the rating number to
   process (unlike the project no need to combine multiple
   ratings) and output common words for that rating
   (or simply concatenate all reviews with that rating to
   a single file)
   * The script will need to check the rating
     number ot figure out what directory it is in
     (`pos` or `neg`).
   * The script will also need to make sure it is a
     valid rating number (there are no reviews with rating 5 or 6.

### Hints
To accomplish this, you'll need to:
1. Create a shell script
2. In the script, use cd to change into the higher level 
   directory
3. Use a conditional to figure out which subfolder
   the rating is in
4. Modify your cat command to use the determined folder 
   and the inputted rating number.
5. If you finished the project, combine this and all of
   your commands into a script (hint -- commands.txt was
   basically a script just with a different extension).


### More Practice (Not Required)
If you want more practice, you could make other modifications
such as (not required for the minilab):
* Instead of accepting 2 arguments, loop through all possible
  values and produce output for all possible rating numbers
* Accept either 2 or 3 arguments.  If there are 3 instead
  of 2, use those as start/end for the range of ratings to
  process together as one.
