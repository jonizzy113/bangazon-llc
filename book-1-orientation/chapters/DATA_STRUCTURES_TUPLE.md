# Python Tuples

Tuples are like lists, but are immutable. They can't be modified once defined. However, finding values in a tuple is faster than in a list.

## Setup

```sh
mkdir -p ~/workspace/python/exercises/tuples && cd $_
touch zoo.py
code .
```

## References

* [Python tuples](https://docs.python.org/3.6/tutorial/datastructures.html#tuples-and-sequences)
* [Introducing Tuples](http://www.diveintopython.net/native_data_types/tuples.html)

## Instructions

1. Create a tuple named `zoo` that contains 10 of your favorite animals.
1. Find one of your animals using the `tuple.index(value)` syntax on the tuple.
    ```py
    # Example
    flowers = ("daisy", "rose")
    flower.index("rose") # Output is 1
    ```
1. Determine if an animal is in your tuple by using `value in tuple` syntax.
    ```py
    animal_to_find = "kangaroo"
    if animal_to_find in zoo:
        # Print that the animal was found
    ```
1. You can reverse engineer a tuple into another tuple with the following syntax.
    ```py
    children = ("Sally", "Hansel", "Gretel", "Svetlana")
    (first_child, second_child) = children
    print(first_child) # Output is "Sally"
    print(second_child) # Output is "Hansel"
    ```
    Create a variable for the first three animals in your zoo tuple, and print them to the console.
1. Convert your tuple into a list.
1. Use `extend()` to add three more animals to your zoo.
1. Convert the list back into a tuple.