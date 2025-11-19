# Project Dev plan

Basically I just want a simple search function to find out:
1. What something can turn into when recycled
2. What materials give you something when recycled

This will require us to read user input, and search through a dictionary to find a particular keyword. I want the user input to not be super precise, as I don't know how to make a python program without using external libraries dynamically ready user input before they hit enter. We will need to store anything we find in the dictionary into two different containers; the first being the item we want and what it turns into, and the second being all the things that give us that particular item.

Here is some pseudocode

```
# returns 2 dictionaries
# 1: Our possible target items, and what they turn into
# 2: All of the things that can turn into our possible target item, along with byproducts
function find_matches(dictionary, search_term) 
    container_one = {}
    container_two = {}
    for key in dictionary
        if search_term in key
            add to container_one
        if search_term in any values
            add to container_two
    return container one and two
```

What does the dictionary look like?
            
    



