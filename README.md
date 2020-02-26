# memory-leaks
how to resolve memory leak


memory leaks occurs when we dynamically creates a memory for the pointer_variable but forget to remove the memory location in the heap.
                to resolve the memory leaks , we need to send the code to valgrind tool and then it will resolve the memory leak issue, it will takes you to the summary there you need to see the heap size is ? then enter a command --check = full;
     by entering this you can resolve the issue 
