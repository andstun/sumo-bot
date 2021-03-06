Check out a quick demo of the bot's functionality [here](https://youtu.be/Wmx6DVFYd20) (note that the bot in the video is not the completed product)

# Introduction

The sport of Sumo has always enthralled audiences, starting from its humble origins in feudal Japan to its present-day worldwide appeal, where the winners of the international Sumo competition are guaranteed a lifetime of fame, prestige, and renown. Recently, robots have taken to the stage, engaging in Sumo competitions. The art of two burly opponents knocking each other out of the ring has been well-preserved within these machine competitions, with many formidable machines having been created to partake in war. 

# Basic functionality and design
La Byamba’s movement is dependent on two factors: staying within the Sumo ring and tracking opponents to push them out of the ring. Line detection is used to keep in the sumo ring, and bot detection is used to drive opponents out of the ring.

To implement line detection, first, a super bright LED and phototransistor are placed at the bottom of the bot. When the LED shines on the dark surface of the Sumo ring, the light will be absorbed, and the bot’s state will not change. However, if the LED shines on the outer white border of the Sumo ring, the light will be reflected towards the phototransistor, which will open a path to ground and stop current from reaching the chip. When this is detected the bot can be programmed to reverse to stay in the ring. 

La Byamba uses an infrared emitter and receiver to perform bot detection. Since the bots all have to be white, the infrared signal sent out by the emitter will bounce off opposing machines and be picked up by the receiver when they are within La Byamba’s line of sight. This allows the bot to track opponents and induce attack protocols. 

La Byamba’s physical design is focused on density: by maximizing weight packed into a small area, it will be able to outmuscle its opponents out of the ring while minimizing its own possible area of contact (much like the real sport of sumo). The bot will also be equipped with a metal plow and have a low centre of mass. The plow is extremely sharp at the tip and low to the ground so that it can dig under the opponent bots and facilitate moving them out of the ring. Additionally, the low centre of mass bolsters La Byamba’s pushing force and increase its defensive capabilities when being pushed. 

La Byamba’s sophisticated processes are driven by its quality hardware. Two motors are used for bot detection - turning them both on enables the bot to move forwards or backwards,  while turning one on and the other in reverse will allow the bot to rotate on its axis. The motors will aid greatly when La Byamba is looking to find and engage other bots in battle.

# Battle Tactics
La Byamba employs a variety of other intelligent strategies to outdo its opponents. In Sumo, speed is critical, therefore, whoever strikes first has a greater chance of victory. The bot will initially run a protocol to approach the opponent on an angle by turning 45 degrees left or right, moving forward, and then turn 90 degrees in the opposite direction and move forward towards the side of the bot. This automatic rush strategy will ideally overpower the bot before the enemy has time to think and run its own program. In case this strategy falls through, a novel heat-seeking detection program will be used. Assuming the initial strategy does not work, the bot will then rapidly move side to side while simultaneously emitting infrared signals and moving forward upon detecting a bot. This will allow La Byamba to continually “wiggle” towards the opponent and never lose track of it. The opponent will then have no choice but to flee to its demise. 


