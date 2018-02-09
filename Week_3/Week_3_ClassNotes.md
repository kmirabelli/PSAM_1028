### Tic Tac Toe Example


```Javascript

var myNestedArrayOfFruit = []
undefined
var myNestedArrayOfFruit = [["","",""],["","",""],["","",""]]
undefined
myNestedArrayOfFruit
(3) [Array(3), Array(3), Array(3)]
0
:
Array(3)
0
:
""
1
:
""
2
:
""
length
:
3
__proto__
:
Array(0)
1
:
Array(3)
0
:
""
1
:
""
2
:
""
length
:
3
__proto__
:
Array(0)
2
:
Array(3)
0
:
""
1
:
""
2
:
""
length
:
3
__proto__
:
Array(0)
length
:
3
__proto__
:
Array(0)
myNestedArrayOfFruit[1][1] = "X"
"X"
myNestedArrayOfFruit
(3) [Array(3), Array(3), Array(3)]
0
:
(3) ["", "", ""]
1
:
(3) ["", "X", ""]
2
:
(3) ["", "", ""]
length
:
3
__proto__
:
Array(0)
myNestedArrayOfFruit[0][2] = "O"
"O"
myNestedArrayOfFruit
(3) [Array(3), Array(3), Array(3)]
0
:
(3) ["", "", "O"]
1
:
(3) ["", "X", ""]
2
:
(3) ["", "", ""]
length
:
3
__proto__
:
Array(0)

```

### .push Method Example

``` Javascript 

myFruitArray
(5) ["Apple", "Banana", "Orange", "Peach", "Pear"]
myFruitArray.push("Pineapple")
6
myFruitArray
(6) ["Apple", "Banana", "Orange", "Peach", "Pear", "Pineapple"]
myFruitArray.length-1
5

```

### .unshift Method Example

``` Javascript

var myColorArray = ["Red","Green","Blue"]
undefined
myColorArray.unshift("Yellow")
4
myColorArray
(4) ["Yellow", "Red", "Green", "Blue"]

```

### .pop Method Example 

``` Javascript

myColorArray
(4) ["Yellow", "Red", "Green", "Blue"]
myColorArray.pop()
"Blue"
myColorArray
(3) ["Yellow", "Red", "Green"]

```

### .concat Method Example

``` Javascript

var ledColorArray = ["red","green","blue"]
undefined
var grayScaleArray = ["white","gray","black"]
undefined
var myLargeColorArray = ledColorArray.concat(grayScaleArray)
undefined
myLargeColorArray
(6) ["red", "green", "blue", "white", "gray", "black"]

```
