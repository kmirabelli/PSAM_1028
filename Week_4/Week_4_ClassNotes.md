
### if & else functions and console.log 

```Javascript

// if condition

var hasFangs = true

if(hasFangs){
    console.log("That's a vampire")
}
That's a vampire

//else condition

var hasFangs = true
if(hasFangs){
    console.log("That's a vampire")
} else {
    console.log("That's a human")
}
That's a vampire 

```

### else if function and console log 

```Javascript

// if & else if condition 

var hasFangs = true
var hasClaws = true

if(hasFangs&&hasClaws){
	console.log("That's a monster")
} else if(hasClaws){
	console.log("That's a werewolf")
} else if(hasFangs){
	console.log("That's a vampire")
} else {
	console.log("That's a human")
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

