# Swift-Basics
Swift Basics Practice Notes

import UIKit

```swift
//String

var firstName="Ramazan"
var lastName="İlter"
print(firstName,lastName) # "Ramazan İlter\n"
var userName="kalawaja"
userName.uppercased()     # "KALAWAJA"
userName.append("1")      # "kalawaja1"
```

```swift
//Integer

var myNumber=20
var myAnotherNumber=30
myNumber.isMultiple(of: 3)            # false
myAnotherNumber.isMultiple(of: 3)     # true
let myFirstNumber=40
let mySecondNumber=7
myFirstNumber/mySecondNumber          # 5 (* Default Result)
```
> `var internetWebDeveloperNumber=10`       //camelCase  
> `var internet_web_developer_number=15`    //snake_case

```swift
//Double

let pi=3.14
print(pi)                         # "3.14\n"
let doubleFirst=40.0
let doubleSecond=7.0
doubleFirst/doubleSecond          # 5.714285714285714 (* Detalied Result)
var integerSelection:Int16=50     
integerSelection=10000000000      # (! : Integer literal '10000000000' overflows when stored into 'Int16')
let doubleThird:Float=5.23
```

```swift
//Boolean

var electricOn=true         # true
electricOn=false            # false
```

```swift
//Defining
let myStringWord:String

//Initialization
myStringWord="Ramazan"
myStringWord.count          # 7
```

```swift
var newGoal:Int
newGoal=20                      # 20
let newOffside:String
newOffside=String(newGoal)      # "20"
newOffside+"70"                 # "2070"
```

