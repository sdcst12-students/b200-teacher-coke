# Review of Tuples and lists

Requirements

You need to remember the following:
* difference between a tuple and a list
* how to access the member elements of a tuple and list
* how to use a for loop with a tuple and list
* how to make a copy of a tuple as a list (or vice versa)

Working with lists:
Some important commands to know:
listname.append()
listname.index()
listName.insert()
listName.count()
listName.pop()
listName.reverse()
listName.sort()

## Assignment:
Open up the file called 200a-Review.py and create the code to make each function work.  You will need to create your own function calls in the main block to test out your functions.  You may use the existing lists to test your functions, or create some of your own.



def getMerge(list1,list2):
    # list 1: expected list or tuple
    # list 2: expected list or tuple
    # add the elements of list2 into list1
    # if the list2 element is in list1, add it at the position where it occurs in list1
    # if the list2 element is not in list1, add it to the end

    return list1


assert getMerge(easy1,easy2) == [5,10,15,2,2,4,4,6,6,8,-2,-4,-6,0.1]