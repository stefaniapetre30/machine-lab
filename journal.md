JOURNAL HOMEWORK - 29/01/2026

I had a lot of trouble getting my circuit and code to operate right during this project. One major issue was that my Arduino stopped responding and would not upload new programs. I later found out that this happened because of wiring issues and because I powered the servo motor directly from the Arduino, which sometimes made the board reset.

I believed the problem was with my coding at first. But once I tested the Arduino with the Blink example and took all the parts apart, I saw that the board itself was working fine. This made me realize that the problem was with my circuit. I fixed this by taking the circuit apart and putting it back together again, verifying each connection carefully.

I also had some trouble with the potentiometer and pushbutton. The Serial Monitor helped me see the values I was sending to the Arduino and how it was reading them. I found out that when you use INPUT_PULLUP, the button reads LOW when you press it, and the potentiometer values go from 0 to 1023.

I utilized the Serial Monitor to debug my project, tested each part on its own, checked my wiring to my schematic, and uploaded basic test scripts. These strategies helped me detect and rectify mistakes. This project taught me the importance of careful wiring, testing one part at a time, and staying patient when solving technical problems.

JOURNAL HOMEWORK - 3/02/2026

1.  The boat is the first module, starting from the left. The boat looks fine and the structure is still there, but it isn't moving at all. I think it was supposed to move or rock a little. The first thing I would do if I could get into the lab is check to see if the motor is getting power. I would try running a very simple Arduino sketch to see if the motor works. I would also check the wiring and pin assignments in the code again. I can't physically test anything right now, and I don't have clear documentation of how it was wired, which makes it hard to debug. It would be a lot easier if I had diagrams or comments in the code.

The carousel is the second module. The building, lights, and horses are all still there, so it looks like it's done. But it doesn't spin, which makes it feel like it's not finished. This is clearly a problem because a carousel that doesn't move doesn't make sense. To fix it, I would first test the motor on its own to make sure the code for rotation is actually running. I would also look to see if anything is in the way or if the gears are slipping. This one is harder to fix because the problem could be with the code, the wiring, or the mechanical system.

The tree is the third module. The tree itself is sturdy and stable, but it doesn't turn as it should. I remember that this part was supposed to turn slowly. I would check to see if the motor is strong enough and getting enough power if I were debugging it right now. I would also check that the code is using the right pins. One problem with this module is that the movement may have been very slow, so it might look broken even though it is working. That makes it harder to tell if it's a design flaw or a real problem.

The telegondola system is behind the tree. You can see the cables and gondolas, and the building looks finished, but nothing is moving. Because it's in the background, it's harder to see clearly, which makes debugging even harder. To begin fixing it, I would first check the motor and pulley system, and then see if the code loop is running all the time. There could be something stuck, or the motor driver might not be set up right. It would be much easier to work on if this section was easier to see and get to.

The Ferris wheel on the right is the last module. The wheel is put together and the gondolas are attached, so it looks like it's done, but it doesn't move at all. This is clearly not working as it should because a Ferris wheel that doesn't turn is pointless. I would test the motor by itself, look for friction, and see if the structure is too heavy for the motor if I could get to the setup. The motor might not have enough power to turn the wheel. I would also check the timing and control code to make sure it is working right.

If I were debugging this project today, I would start by separating each module and testing it with very simple Arduino programs. Before I moved on to more complicated logic, I would check the power supplies, wiring, and motor drivers. You could also use the serial monitor more often to make sure that the code is running correctly.
I was thinking about using Arduino and mechanical pieces instead of a screen to make a real-life version of Pac-Man for my project. I don't think this is okay, though. This is still a relatively new notion, and nothing is set in stone yet.




2. I chose Pac-Man since it's a famous game that almost everyone recognizes. It appears like it might really happen that you could go through a maze and pick up dots. There are also obvious regulations, including not going near ghosts and trying to get everything. This makes it simple to turn into an actual game.

The most important point:

The fundamental idea is to construct a true maze board that looks like a Pac-Man map. You wouldn't play on a screen; you'd play on a physical board. Pac-Man would be a small piece that moves through the maze, like a ball or something with a magnet.

We could make the maze out of wood, cardboard, or plastic, depending on what we have. An Arduino would have motors and connections that control movement under or within the board.

Regulations:

The player can move Pac-Man with buttons or a joystick.

You can tell the Arduino to move Pac-Man in a given direction by hitting a button, but only if there isn't a wall in the way.

Making it work:

In real life, Pac-Man would walk through the maze instead of on a computer. One option is to employ magnets, with Pac-Man on top and a magnet underneath that moves it. This concept came to me as we talked about how to move things with sand. Another way is to utilize tracks or rails that the item can slide on.

The Arduino would inform the motors what to do and keep Pac-Man from hitting barriers.

Dots and Points:

For the dots, I could put in miniature buttons, beads, or sensors. When Pac-Man steps on one, it is "picked up." The Arduino can keep track of how many you have and show it with lights or sounds.

Power pellets may be bigger pieces that do something special, like make the ghosts move more slowly.

Spirits:

The ghosts would also be genuine things that move around in the maze. They might move about randomly, follow set paths, or try to catch Pac-Man in a simple way.

Every ghost might have its own engine. If a ghost touched Pac-Man and a sensor picked it up, he would lose a life.

Winning and Losing:

You win if you get all the dots.
You lose if a ghost catches you too many times.

The game would use:

- LEDs that last a long time

- A buzzer for sound effects

- A score display with numbers might work.

Things that work mechanically

There would be a lot of mechanical parts in this project, like motors, gears, rails, magnets, pulleys, moving platforms, and so on. If the maze is modular, I could even be able to change it later.

How It Would Work:

1. You press a button.

2. It reads it with Arduino.

3. The engine makes Pac-Man move.

4. The sensor checks for dots or ghosts.

5. Get an update on your scores or lives.

6. Lights and noises react.

7. The game is still going on.

Issues:

1. Things that could be hard:

2. Making sure everything goes together the right way

3. Stopping parts from getting stuck

4. Making the motion flow smoothly

5. Looking after all the wires

6. Making it stronger so it won't shatter

Thinking about it

This idea is great since it lets you code, build, and be creative all at the same time. It makes me think about how games work in the actual world, not just on a screen, like P5.js. I think it would be really fun and interesting to make a real-life Pac-Man game, even though this is only a rough idea for now.

The diary entry is only for ideas, and my final project might be different, but here is where I'm starting.

![image](sketch.png)

