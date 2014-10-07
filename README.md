# Iterators Lab
## Functional Programming


### Description

In the iterators lab we will be continuing our exploration of iterators and building a few more useful methods. These methods will belong to an Iterators namespace, which we discussed in class. We also will try to use various testing methods to verify that our code is working.


### Phase-1

Research the following term and summarize your findings on it two to three sentences:

* `higher-order function`
a higher-order function is a function that 1) takes one or more functions as an input and/or also 2) outputs a function, allowing us to manipulate actions not simply values. 

Pretending we implemented the following methods, update this README with a description of each of the following and an example you've created:

* `max` the max function outputs the highest-value element from the array. 
* `min` the min function outputs the lowest-value element from the array.
* `each` the each function executes a provided function once per array element. 
* `map` the map function executes a provided function once per array element and outputs a new array of the results
* `filter`: [note](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/filter)
the filter method executes a test implemented by a provided function and creates a new array from all elements that pass the test
* `reduce`: [note](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/reduce)
the reduce method applies a function against an accumulator and each value of the array (from left-to-right) has to reduce it to a single value.
* `reject`: [note](http://underscorejs.org/#reject)
the reject method executes a test implemented by a provided function and modifies the array by eliminating all elements that fail to pass the test. 

Use the notes provided to help guide you explanation.


### Phase-2

* Write a test in the `spec` folder for `min` and implement it in the `src/iterators.js` folder. There is a test for a `max` method already if you'd like to use that as inspiration.

* Re-implement the `each` function, but write the spec for it first. Continue this exercise with `map` and `filter` and write tests first!


### Phase-3

Implement the remaining iterator methods in the namespace and add tests for each one of them. Make sure that they return the correct data as well as datatype, and implement tests for edge cases (empty arrays, negative numbers).

