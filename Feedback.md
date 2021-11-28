## Feedback

Your formatting on the Readme sucks. The thing in the code block should be the name of the file, not just `File 1 Name`. 
I mean, it's fine in terms of me being able to read it, but I think I expected a bit better finished product given the, ahem, timeline. Also,
leaving your reflections blank! C'mon! :-)

Your notebooks within Task 1 are very clear, however, and I like the steps listed in 1a. On the other hand, I think all this notebook
does is print the first line. That's fine to have exist, but it doesn't make sense as part of your solution. Are you just writing down
which files have headers and which don't? Why not use the computer to store that information!

Do all your imports at the top of your files, not interleaved with your code. 

Again, 1b is fine to have as code you've written, it just doesn't make sense as the clean submission to me... You've got code that
tests line lengths, so you should be using that rather than code like this: 
```
if zipped_file == ('transArchive_201207_201209.csv') :            
    if 326345 == idx :
        line[5:8] = [' -'.join(line[5:8])]
```                            
The above code is just very fragile. 

After 1a, you switch from semi-nicely formatted markdown cells to just screaming everything at me in headers. 

## That is a weird way to write comments and doesn't seem very professional. See what I mean?

Well, the "unsustainable" approach continues into 1b-iii. This gets the job done, it's just the opposite of elegant. 

1c seems to put the pieces together. I guess part of me is intrigued by seeing how the sausage got made, but it would 
have been better to just do a `Task 1.ipynb` and then have a folder with the code you used to get to that point. 

This is a weird table name: `wedge-project-fall2021-92691-f3182a53adb6`. What would a human have named it?

The upload from 1d could be done a bit more elegantly also, but looks like it works. Whew, Task 1 in the books...

Task 2 is good except for one small point, that seems worth calling out. You create a query object called `random_trans`
and then you do some things like print the first row. That will "use" the first row for printing and then, when you ask
for the next record, will start on record 2. So be careful playing around with objects and then not "refreshing" them when you go 
to do the real work. I'm guessing you're missing the first transaction row for your random sample. Just something to keep in mind. 

Task 3 looks pretty good. There are some slightly fancier ways you can do it (see solutions) but this works. 

Nice job getting to the finish line. 

