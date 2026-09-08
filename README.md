# Assignment 1: Haskell Basics

In this assignment you learn the basics of the Haskell programming language.
It is very important to work carefully through the assignment, since the next five weeks build
up on this fundament!

The different topics of this assignment are all covered by the first part of the excellent and strongly recommended book ["Programming in Haskell"](https://www.cs.nott.ac.uk/~pszgmh/pih.html) by Graham Hutton.

## Instructions
1. Install [ghcup](https://www.haskell.org/ghcup/).
2. Use ghcup to install the recommended versions of ghc and cabal: 
   - ghc version 9.10.3 \
   `> ghcup install ghc 9.10.3`
   - cabal version 3.16.1.0 \
   `> ghcup install cabal 3.16.1.0`
3. Install [VS Code](https://code.visualstudio.com/).
4. Install the [Haskell Extension](https://marketplace.visualstudio.com/items?itemName=haskell.haskell)
5. Open VS Code directly on the folder `AS01_HaskellBasics`.
6. Open the file [Main.hs](./Main.hs) and start working through it top to bottom.

## Commands
- Run all tests: `cabal test --test-show-details=direct`
- Only run tests for a particular section:\
   `cabal test --test-show-details=direct --test-option=--match --test-option="8."`
- Start a REPL: `cabal repl test:tests` \
This starts ghci (a read eval print loop) to experiment with your code.
Save your file after making changes and reload it into the repl using `:reload` or `:r`.
`:q` terminates the session.
`:t e` prints the type of expression e.

## Feedback:
1. Fork the assignment repository (please keep the name).
2. Create a branch called `solution`.
3. Solve the assignment on that branch and push it.
4. Open a pull request in your own fork: base repository = your fork, base branch = `main`, compare branch = `solution`.  
⚠️ GitHub preselects my repository as the base → you must change it.
5. Add a comment on the pull request mentioning `@danielkroeni`, and leave the pull request open (don't merge it).

I'll reply with review comments directly in the pull request. If you push more commits, mention me again.
