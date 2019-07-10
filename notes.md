Data location must be "memory" for return parameter

    breaking change, add memory keyword.

Function state mutability can be restricted to pure function
    change view to pure


    Functions can be declared view in which case they promise not to modify the state.

    Functions can be declared pure in which case they promise not to read from or modify the state.


