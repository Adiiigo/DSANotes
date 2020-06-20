Backtracking refers to the type og algorithm which tries to exhaut or find all the possible answers using recursion.

Basic Algorithm :
```
bool solve(configuration conf) :
    if(no more choices) : //Base case
        retuen (conf is the goal state)
        
    for(all available choices) :
        try one choice c 
        ok = solve(conf with choice c)
        if(ok == true) :  
            return true 
        else :
            retrun false
            
     return false //no more choices to explore and we exhauted all the possible cases.
```
        
    
     
