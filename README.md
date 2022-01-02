# Basic Chess 1V1
Thank you to Github User [nagayev](https://github.com/nagayev) for assisting with the build instructions regarding CMAKE as well as some refactoring.

## About

This is a chess program that I created in the winter of 2021. I am a big fan of the game and I always wanted to make the game on my own.

This video was really helpful for me: https://www.youtube.com/watch?v=kwQk5A26cis&t=822s

To make this be able to run, you will need to link both the SDL library, and the SDL_Image library. Eventually I will make this into a standalone download, but I believe that I will wait
until I implement an actual artificial intelligence to play against.


## Building
This project use CMake for building.  
You need to install cmake and sdl with sdl-image.  
Then type `cmake .` and you will get .vsproj file/Makefile or XCode project (depending on your OS)  
