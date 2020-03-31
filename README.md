

// array of closures 
var i = 0
var closureArray = [()->()]()
for _ in 1…5 {
closureArray.append {
print(i)
}
i += 1
}
// here i will be 5
closureArray[0]() // prints 5
closureArray[1]() // prints 5
closureArray[2]() // prints 5
closureArray[3]() // prints 5
closureArray[4]() // prints 5


