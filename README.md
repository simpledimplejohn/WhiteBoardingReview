# __White Boarding Assignment Epicodus__
### by [John Blalock](https://github.com/simpledimplejohn) 

### __Description__

_Solution to the prompt: Question #2: Array Deduping
Write an algorithm that removes duplicates from an array. Do not use a function like filter() to solve this. Once you have solved the problem, demonstrate how it can be solved with filter(). Solve the problem with and without recursion._

_Example_

`Input: [7, 9, "hi", 12, "hi" 7, 53]`

`Output: [7, 9, "hi", 12, 53]`

### __Technologies Used__

* _JavaScript_
* _Node.js_
* _Functional Programing



### __Setup/Installation__

1. _Copy the following code_ 
```
function deDupe(array) {
    const newArray = []
    for(let i = 0; i < array.length; i++){
        for(let j = 0; j < array.length; j ++){
            if(array[j] !== array[i]) {
                newArray.indexOf(array[j])
                //console.log(i,j)
            }
        }
    }
    return newArray
    
}

console.log(deDupe([7,9,"hi",12,"hi",7,53]))
const array = [7,9,"hi",12,"hi",7,53];
// returns the index where the character or ellement first appears on a string or array
// only return when it first appears
const filterArray = array.filter((e, i) => array.indexOf(e) === i )
                              

console.log(filterArray)
```


### __Known Bugs / Future Goals__
No bugs have been found or reported. Please contact the authors if you experience poor performance.



### __License__
This software is licensed under the [BSD license](license.txt).

[![License](https://img.shields.io/badge/License-BSD%202--Clause-orange.svg)](https://opensource.org/licenses/BSD-2-Clause)

Copyright (c) 2021 

### __Contact Information__
 __John Blalock simpledimplejohn@gmail.com__
