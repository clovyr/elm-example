# About Clovyr Code

Clovyr Code delivers full-featured VSCode in the browser, connected directly to 
any public or private git repository. 

Learn more and try it out at [clovyr.app/code](https://clovyr.app/code)

Tip: Use `` CTRL+` `` to show/hide the terminal, and `CTRL+SHIFT+5` to open a new 
terminal. [More shortcuts](https://help.clovyr.io/code/keyboard-shortcuts)

# Clovyr Code Elm examples

This repository includes sample Elm apps for the
purpose of demonstrating the Clovyr Code Elm development environment.

[TodoMVC](http://todomvc.com/) is a project which offers the same Todo application 
implemented in several popular programming languages.

## Running the examples

1. Navigate to one of the example directories:  
`cd ~/git/github.com/clovyr/elm-example/examples/todomvc`
1. Build the project  
`elm make src/Main.elm --output=elm.js`
1. Run the server  
`python3 -m http.server 8080`
1. In a new browser tab, enter the url of your Clovyr Code instance
prefixed by `8080-`
   * The URL for your instance is found in the green bar at the bottom of 
   the application space
   * For example, if your Code environment is `https://happy-otter.wnext.app`,   
   the served application is at `https://8080-happy-otter.wnext.app`. 
1. To stop the server, enter `CTRL+C` in the terminal where the program was
invoked

## Documentation

Find more documentation at https://help.clovyr.io.
