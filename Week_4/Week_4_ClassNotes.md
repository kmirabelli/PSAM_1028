
### if/else/else if functions and console.log 

```Javascript

// if condition

var hasFangs = false
undefined

if(hasFangs){
    console.log("That's a vampire")
}
undefined
var hasFangs = true
undefined
if(hasFangs){
    console.log("That's a vampire")
} else {
    console.log("That's a human")
}
That's a vampire 

```

### Needs revision

```Javascript

// if & else if

var hasFangs = true
undefined
var hasClaws = true
undefined
if(hasFangs){
	console.log("That's a vampire")
} else if(hasClaws){
	console.log("That's a werewolf")
} else if(hasFangs && hasClaws){
	console.log("That's a monster")
} else {
	console.log("That's a human)
}

```

#### While test 

```Javascript

//while test

var sheepCounter = 0

while(sheepCounter < 10){
    console.log("I have counted" + sheepCounter + " sheep!")
sheepCounter++
}

VM1277:3 I have counted0 sheep!
VM1277:3 I have counted1 sheep!
VM1277:3 I have counted2 sheep!
VM1277:3 I have counted3 sheep!
VM1277:3 I have counted4 sheep!
VM1277:3 I have counted5 sheep!
VM1277:3 I have counted6 sheep!
VM1277:3 I have counted7 sheep!
VM1277:3 I have counted8 sheep!
VM1277:3 I have counted9 sheep!
9

```

#### For test 

```Javascript

var timesToSayHello = 10

undefined
for (var i = 0; i < timesToSayHello; i++) {
	console.log("Hello!")
    }
Hello!

```

