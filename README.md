# Swift: Tournament

Tally the results of a small football competition.

Tally the results of a small football competition. Based on an input file
containing which team played against which and what the outcome was
create a file with a table like this:

```
Team                           | MP |  W |  D |  L |  P
Devastating Donkeys            |  3 |  2 |  1 |  0 |  7
Allegoric Alaskans             |  3 |  2 |  0 |  1 |  6
Blithering Badgers             |  3 |  1 |  0 |  2 |  3
Courageous Californians        |  3 |  0 |  1 |  2 |  1
```

What do those abbreviations mean?

- MP: Matches Played
- W: Matches Won
- D: Matches Drawn (Tied)
- L: Matches Lost
- P: Points

A win earns a team 3 points. A draw earns 1. A loss earns 0.

The outcome should be ordered by points, descending. In case of a tie, teams are ordered alphabetically.

###

Input

Your tallying program will receive input that looks like:

```
Allegoric Alaskans;Blithering Badgers;win
Devastating Donkeys;Courageous Californians;draw
Devastating Donkeys;Allegoric Alaskans;win
Courageous Californians;Blithering Badgers;loss
Blithering Badgers;Devastating Donkeys;loss
Allegoric Alaskans;Courageous Californians;win
```

The result of the match refers to the first team listed. So this line

```
Allegoric Alaskans;Blithering Badgers;win
```

Means that the Allegoric Alaskans beat the Blithering Badgers.

This line:

```
Courageous Californians;Blithering Badgers;loss
```

Means that the Blithering Badgers beat the Courageous Californians.

And this line:

```
Devastating Donkeys;Courageous Californians;draw
```

Means that the Devastating Donkeys and Courageous Californians tied.

Your program should only process input lines that follow this format.
All other lines should be ignored:
If an input contains both valid and invalid input lines,
output a table that contains just the results from the valid lines.

In order to use Swift, you must be running Xcode version 7.3 or greater which is available at [Apple's developer center][appledev].

[appledev]: https://developer.apple.com/xcode/downloads/

The exercises use XCTest.

See [this guide][exercism-xcode-swift] for details about how to create the project in XCode and run the tests.

[exercism-xcode-swift]: https://github.com/exercism/xswift/blob/master/docs/TESTS.md

# Source

This exercise is from the [Swift][swift] track on [Exercism][exercism]

[exercism]: http://exercism.io
[swift]: http://exercism.io/languages/swift



