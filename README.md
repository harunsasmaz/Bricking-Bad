# Bricking Bad

Software Engineering Course Term Project

Developed with Java Swing

## About the Project

Project consists several parts as the following.

### Bricks

#### Simple Brick

Just simple oldschool brick that we all familiar with.

#### Half Metal Brick

Bottom side of this brick is metal and it can be broken if it is hit by above.

#### Mine Brick

It creates an explosion and destroys all bricks around a specific radius.

#### Wrapper Brick

These bricks hide either a power up or an enemy inside with a probability until it is hit.

### Aliens

#### Cooperative Alien

These aliens are our ally, they pick a row and destorys all bricks on that row. However, if one of them is hit, then they stop appering anymore.

#### Protecting Alien

Like half metal bricks, they position at the bottom line and cannot be destroyed from the bottom. 

#### Repairing Alien

These aliens build a brick for every 5 seconds

#### Drunk Alien

These aliens have no identiity, they randomly pick a behavior.

### Power-ups

Power-ups you have appear at the left bottom, you need to catch them while they are falling.

#### Fireball

These ball power-up helps to crack half metal bricks and protecting aliens.

#### Gang of balls

Ten balls are created right after finding this power-up

#### Chemicall ball

For 30 seconds, this ball destroy everything it passes through.

#### Magnet

For 30 seconds, ball sticks to paddle and you can use <key> space </key> to throw it again.

#### Expand Paddle

You can use it to double the size of paddle for 30 seconds.

#### Destructive laser

Two lasers appear at the both ends of the paddle, you can use 5 lasers and they destroyed everyhing on their way.

### Gameplay

![](demo.gif)
