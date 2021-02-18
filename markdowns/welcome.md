New to CodinGame? Welcome!

Everything seems a bit complex and overwhelming? Worry no more, and read on!

# Our mission

**Our goal is to empower developers, no matter their educational or professional background, to learn from their peers, level up their skills and showcase their talent.**

_Disclaimer: Except for the content created by the community in the **Learn** section, CodinGame doesn't provide any tutorial to learn the basics of programming from scratch. We highly recommend taking a tutorial online to learn these basics before heading to the **Practice** section and trying to solve coding puzzles._

On CodinGame, you'll be able to:

- practice your programming skills and learn new ones
- find a job and practice programming interviews
- code for fun and chill
- hang out with other passionate coders
- strengthen your confidence and motivation to code

# Getting Started

There are a lot of different activities to discover on CodinGame. Here's a [complete overview](https://virtual-atom.com/codingame/introduction/) of them, written by one of our members, Thomas!

We recommend following the **quest map** learning paths. You'll find the map on your [home page](https://www.codingame.com/home).

## How it works

In computer programming, **standard streams** are preconnected input and output communication channels between a computer program and its environment when it begins execution. The three input/output (I/O) connections are called standard input (**stdin**), standard output (**stdout**) and standard error (**stderr**).

CodinGame's model is to communicate with text, via these streams: your program is given inputs (the data needed to solve the problem) in the stdin and you need to print out the requested answer in the stdout.
Hence, one of our taglines being: _"Read stdin, Flush stdout"_

## Protocol

The default code, given in all CodinGame puzzles, already parses the inputs in stdin, does nothing with them and prints a default output in the stdout.

You can find more details about this default code and what to expect from the inputs and how to format your answer at the bottom of any puzzle statement.

## Debugging

You can use the stderr for debugging purposes. Debug messages will show in the console output (at the bottom left).

You can not use breakpoints.

# Coding puzzles

## Puzzle validation

Most puzzles work with a system of test cases: visible IDE tests to help you verify your code solve the given problem, and corresponding hidden tests, called _validators_ for the system to verify you didn't hardcode the tests.

You solve these puzzles by passing all validators. Some puzzles (Code Golf, Optimization) will ask you to pass the tests _and_ to optimize a specific criterion, and you'll be then ranked against other players based on the criterion.

## In/Out puzzles

Most puzzles in the **Practice** section are In/Out puzzles. You're given a problem, inputs to read in the stdin, and our system expects your program to print the requested answer in stdout, depending on the inputs.

You can have a look at the test cases by clicking on the button at the top right of the test cases panel.

<img src="https://www.codingame.com/servlet/mfileservlet?id=32176742376130" width="400" style="margin-left: auto;margin-right: auto;display: block;">

For each test, you can find on the left, the input data as it's sent to you in the stdin, and on the right, the expected output on stdout.

<img src="https://www.codingame.com/servlet/mfileservlet?id=32177207300883" width="400" style="margin-left: auto;margin-right: auto;display: block;">


## Gameloop puzzles

Other puzzles contain an "infinite" while loop in the default code. It's the "game loop".

Each iteration of the while loop corresponds to a turn of the puzzle where your code must read input data in stdin and output a "move" in stdout.

The game loop is actually not infinite: there is a maximum number of turns allowed to solve each puzzle. Once your program sends the expected output or reached the expected state, the referee program (on CodinGame side) will end the loop.

It's really important to continue reading all input data on the stdin each turn; else, your program will desynchronize from the referee program.

With the same idea, if you start reading the input data of turn n+1 on the stdin without having sent a response in the stdout at turn n, the referee program will consider that your program did not respond in due time (timeout).

## Bot programming games
 
Bot programming games are multiplayer games with a game loop. Your goal is not to output a solution but to create a bot (an AI) capable of playing a game in the given environment. There are no test cases to pass.

You're required to submit your bot to the arena of the game to be ranked against other players. Our system automatically play matches between bots in the arena every time a new bot, or a new version of a bot is submitted.

Here's a [guide to get started in bot programming games](https://www.codingame.com/playgrounds/53785/tutorial-for-bot-programming-on-codingame). It's actually simpler than it looks!


# Contributing to CodinGame

Most CodinGame puzzles are created and moderated by the community itself. Check [how you can contribute](https://www.codingame.com/playgrounds/40701/contribute---help/why-contribute) too to our platform and its amazing community.

# Getting help

Some easy puzzles have a hint panel on the left side of the IDE. Use it!

Each puzzle is linked to a specific forum thread. You can find tons of tips about each puzzle there.

Puzzles also have a presentation page with details about the problem, tags and possibly external resources links. Use them!

You can ask the community in the chat or on Discord if you have a problem. People chatting there are quite friendly but remember that they don't _have to_ help you.

99,9% of the time, the bug will be in your code and not in the puzzle. If you have an issue, double-check your code and search the statement for edge cases you might have missed.

After you solved a puzzle with a language, you can access solutions from other players in that language. You can learn a lot there!

________

Feel free to ask questions or suggest ways to improve this guide in the comments section below.