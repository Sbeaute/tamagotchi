## Build a Tamagotchi

What is a tamagotchi? According to [wikipedia](https://en.wikipedia.org/wiki/Tamagotchi), the name is a portmanteau combining the Japanese word tamago (たまご), which means "egg", and the English word "watch". Most Tamagotchi characters' names end in tchi (っち) in Japanese, with few exceptions.

A tamagotchi has a few properties:
```js
/*
- name
- weight
- age
- birthday
- description
- hungerLevel
- happinessLevel
- attentionLevel
- lifeStage // Baby, Child, Teen, and Adult
/*
```

A few states:
```js
/*
- isHungry
- wantsToPlay
- isHappy
- needsAttention
*/
```

And few behaviors:
```js
eat() {
/* feeding should satisfy hunger, depending on what you feed it, and may increase weight
 grass, meat, tofu, bread, candy, etc…
*/
}
speak() {
 /* what needs does your tamagotchi have? */
}

play() {
 /* playing with your tamagotchi should increase happiness, satisfy need for attention, and may decrease weight */
}
```

Usage:
```js
tamagotchi = new Tamagotchi('Mesutchi') // Hatch your tamagotchi. Names usually end in tchi (っち)
tamagotchi.age // 0
tamagotchi.birthday // today's date
tamagotchi.weight // 1 
tamagotchi.description // 'A <lifeStage> tamagotchi named <name> born on <birthday> weighing <weight>'
tamagotchi.speak() // 'Mesutchi is <some state>'
```

## Bonus:
Continue to implement a real tamagotchi, adding the following properties and methods:
Properties:
```js
/*
- disciplineLevel
- isDisciplined
- needsBathroom
- itPottyTrained
- isSick
- sleeping
*/
```

Methods:
```js

sleep()

wake()

scold() {
 /* fills discipline level, reduces happiness level */
}

useBathroom()

view() {
 /* displays image of the tamagotchi */
}

```
What else can your tamagotchi do?


