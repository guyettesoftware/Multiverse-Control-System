# Multiverse-Control-System
Version control with no destructive commands

# Point of View
You create a multiverse. You create branches. Lots of branches.
So many, that it's overwhelming. Things get cluttered. So how do we clean them?

Point of View. Point of view allows you to show all the branches you want.

For example if we create the multiverse...

```
Multiverse_1
    Animals/Cats/mylizard.jpg
    Animals/Dogs/myPotato.jpg
```
          
you notice that "mylizard.jpg" and "myPotato.jpg" are in the wrong places. 

Point of View: Second Multiverse Only, Comment: "Viewing the corrected version where all the animals are in their correct paths.
Multiverse/Animals/Cats/mylizard.jpg
          /Animals/Dogs/myPotato.jpg
          Multiverse_2/Animals/Cats/mycat.jpg
                    /Animals/Dogs/mydog.jpg

Now, if we run the POV command, standing for Point of View, we only see:
```
Multiverse_2/Animals/Cats/mycat.jpg
          /Animals/Dogs/mydog.jpg
```
