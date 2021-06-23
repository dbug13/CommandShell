# Command Shell F# Scaffold Project

## Project Overview

The overall goal of this project is to create a `REPL` shell scaffold project
written in `F#`.

### Goals of The `REPL` shell scaffold project

- Initially will be a Console `REPL` written in `F#`
    - **Nice To Have**: Scaleable to plug into a GUI framework like `Avalon`.
- Create an `F#` library that parses user input.
    - Provides a method to parse a string of text into a `Command` object.
    - Provides a method to validate a `Command` against a user supplied `callback method` that allows the user to validate any parsed `Comamnd`.
    - Provides a method to output any errors the library may produce.
- What are `Commands` ?
    - `Commands` should work like they do in your operating system's `Terminal` application.
    - A `Command` should be interpreted when the user hits the `Return` key.
    - Once a `Command` is executed any output produced by the command should be printed out to the user's screen.
    - After a `Command` is executed, display the user prompt and wait for the user to type a `Command` and press the `Return` key.  


## Examples

**TODO**: Add screenshots demonstrating the App in action.
