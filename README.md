# Multiverse-Control-System
Version control with no destructive commands

# Point of View
You create a multiverse. You create branches. Lots of branches. You make mistakes.
So many, that it's overwhelming. Things get cluttered. So how do we clean them?

Point of View. Point of view allows you to show all the branches you want.

For example if we create the multiverse...

```
Multiverse_1: Current POV
    Cats/mylizard.jpg
    Dogs/myPotato.jpg
```
          
You notice that "mylizard.jpg" and "myPotato.jpg" are in the wrong places.

So you create a new branch Multiverse_2 and make the corrections. 
Notice: Multiverse names increment by 1 automatically, and cannot be changed.

Running the "POV" command meaning "Point of View", you get:
                    
```
Multiverse_1: Current POV
    Cats/mylizard.jpg
    Dogs/myPotato.jpg
    Multiverse_2: Created to put correct photos in correct locations 
        Cats/mycat.jpg
        Dogs/mydog.jpg
```  

That's great, but you only want to see Multiverse_2 when running the POV command

So you run the command 

```
POV Multiverse_2
```

Which returns:
```
Multiverse_2: Created to put correct photos in correct locations 
    Cats/mycat.jpg
    Dogs/mydog.jpg
```  
