# Asteroid game
<p>A desktop game involving the destruction of flying asteroids using a spaceship, created with C# and XAML.</p>

You can <a href="https://github.com/igor-muram/Space/raw/main/Space/Publish.zip" target="_blank">download</a> and watch the created game.

## Description

* The level is started by clicking on the «Start game» button.
* At the beginning of the level the ship has 5 health points and 1 laser.
* Asteroids appear at random locations on the playing field and have a random size and a random amount of health.
* When a laser hits an asteroid, the asteroid's health is reduced.
* When a ship and an asteroid collide, the amount of health of the ship is reduced. 
* If the amount of health of the ship is less than the damage caused by the asteroid, then the ship is destroyed and the game ends.
* The number of asteroids on the playing field at the same time and the amount of their health increases as the level increases.
* At the top of the screen is the number of points scored by the player and a progress bar.
* The background moves during the game.
* All of the icons used for the boosters are self-drawn.
* When an asteroid is destroyed, a booster of some type may appear with some chance.

## Main menu

![image](https://user-images.githubusercontent.com/54866075/126881369-3ac0bc92-66b2-4026-bd3f-3a9795447395.png)

## Start game

![image](https://user-images.githubusercontent.com/54866075/126881383-73353c4e-7319-4d5c-b9e5-2a93cf98d1c3.png)

## Asteroids

![image](https://user-images.githubusercontent.com/54866075/126881408-4630edc3-c5aa-47da-b651-23903486cdca.png)

## Booster Chainsaw

* The booster is active for 5 seconds.
* When booster is active, the ship does not take damage when it collides with the asteroid and can also deal damage to the asteroid with the chainsaw.

![chainsaw](https://user-images.githubusercontent.com/54866075/127874843-b8717552-3954-4341-b152-ce5db4e040d4.png)

## Booster Shield

* The booster is active for 5 seconds.
* When booster is active, the ship does not take damage when it collides with the asteroid.

![shield](https://user-images.githubusercontent.com/54866075/127874914-8c31c16c-6e71-480a-bb97-f134a5f42700.png)

## Booster Lazer

* If you get a booster, the number of lasers increases until the next collision with the asteroid.
* The number of lasers may vary from 1 to 3.
* With each asteroid collision the number of lasers decreases by 1 until it reaches the minimum number.

![lazer](https://user-images.githubusercontent.com/54866075/127874943-c899fc51-21da-4f21-8454-ff718dfd1d74.png)

## Booster HP

* When you get a booster, the amount of health points of the ship increases by 5.

![hp](https://user-images.githubusercontent.com/54866075/127874967-94edf3ec-2cf4-4749-bc94-04148de6e631.png)

## Booster Bomb

* When you get a booster, all asteroids on the playing field disappear.
* Boosters do not appear when destroying asteroids with a bomb.

![bomb](https://user-images.githubusercontent.com/54866075/127875609-93b14d60-f8b8-4d76-b2e7-dd753e03162b.png)

## Booster Damage

* When you get a booster, the damage of the ship increases by 5.

![damage](https://user-images.githubusercontent.com/54866075/127875053-2b1f4adc-4cc1-4481-90fc-7db8812a067f.png)

## Level Passage

![win](https://user-images.githubusercontent.com/54866075/127875333-67dfb1f4-9d87-4182-8be5-ef13dfad59d1.png)

## Next level

![2lvl](https://user-images.githubusercontent.com/54866075/127875361-60455051-e8dd-48d8-bf38-955b511882a8.png)

## Game over

![image](https://user-images.githubusercontent.com/54866075/126881393-2323be54-2a89-424b-98ab-f7b21b2e180a.png)
