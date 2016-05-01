## TeachCraft 

Hi guys!

If you're reading this, it's too late.

Just kidding. This is a pilot project idea to incorporate Minecraft into teaching python. Glad you're interested in trying it out!

All that is needed to get started is downloading the code in this repo and installing java on your system (full instructions in the [setup guide](https://github.com/ac-cs/TeachCraft-Challenges/blob/master/setup.md)).

If you need any help along the way, feel free to email Mason or Mr. Drenth (Mason is the only Mason in the school, so typing "Mason" and having it autocomplete should work :p)

### Lessons & Setup

[Initial Setup](https://github.com/ac-cs/TeachCraft-Challenges/blob/master/setup.md): Get minecraft running, get connected to the server.

[Lesson 1](https://github.com/ac-cs/TeachCraft-Challenges/blob/master/lesson_1.md): Teleport your character to a point you define in code.

[Lesson 2](https://github.com/ac-cs/TeachCraft-Challenges/blob/master/lesson_2.md): Make a path of something (flowers, lava, fire) follow behind you while you walk. 

[Lesson 3](https://github.com/ac-cs/TeachCraft-Challenges/blob/master/lesson_3.md): Give your character the ability to walk on water (by turning water below your character into ice).

[Lesson 4](https://github.com/ac-cs/TeachCraft-Challenges/blob/master/lesson_4.md): Create a building programmatically

[Lesson 5](https://github.com/ac-cs/TeachCraft-Challenges/blob/master/lesson_5.md): Create a pyramid programmatically

[Lesson 6](https://github.com/ac-cs/TeachCraft-Challenges/blob/master/lesson_6.md): Use an algorithm to construct the pyramid by analyzing the pattern you discovered in lesson 5!

[Lesson 7](https://github.com/ac-cs/TeachCraft-Challenges/blob/master/lesson_7.md): Create a magic system that listens to Minecraft chat, and executes your pre-defined spells!

[(Advanced) Lesson 8](https://github.com/ac-cs/TeachCraft-Challenges/blob/master/lesson8/lesson8.py): Learn how to import an image into minecraft pixel art using Python Imaging Library.

### Minecraft Docs
- [pi version](http://www.stuffaboutcode.com/p/minecraft-api-reference.html) Has most of the basics of the python api
- [our version](https://github.com/zhuowei/RaspberryJuice) Has the additional things our python api supports, above and beyond the pi version
- [Minecraft block ids](http://minecraft-ids.grahamedgecombe.com/)

### Notes
- Player location from the python api will not match the same retrieved from the server.
    This is because raspberryjuice calculates it from the spawn point, while the server calculates it from 0,0,0.
    To fix, run this as an admin:
    setworldspawn 0 0 0
    (Is this still an issue? o.O)
