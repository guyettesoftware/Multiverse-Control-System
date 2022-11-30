# Multiverse-Control-System
Version control with no destructive commands, and roles built in.

# Commands
## CB:  
Create new branch.

## PNB: 
Propose new branch if you don't have direct Create Branch permissions.

## POV "your_multiverse_name_here_without_quotes": 
Changes the current POV to the specified multiverse

## POV "your_multiverse_name_here_without_quotes", Filters{onlyThisMultiverse = true}: 
Changes the current POV to the specified multiverse, and does not show any branches off it

## pov_nickname = POV "your_multiverse_name_here_without_quotes", Filters{onlyThisMultiverse = true}: 
Saves a specific POV to a varriable name to indicated its meaning. For example:

```
developer_pov = POV "developer_multiverse", Filters{onlyThisMultiverse = true}: 
```

# Set User POVs
```user_name_123.addPov(developer_pov)```

# Point of View
You create a multiverse. You create branches. Lots of branches. You make mistakes.
So many, that it's overwhelming. Things get cluttered. So how do we clean them?

Point of View. Point of view allows you to show all the branches you want by using filters.
We'll start off simple with no filters.

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
