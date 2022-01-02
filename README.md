# Basic Chess 
![Screenshot at 2022-01-02 20-46-16 (2)](https://user-images.githubusercontent.com/73020056/147887842-45c5ed84-fb7d-42f6-845f-ff62bd640e00.png)

## About

This is a chess program that I created in the winter of 2021. I am a big fan of the game and I always wanted to make the game on my own.  
This version is a basic 1v1 chess game, so you can run the game and play with one of your friends. 

I based my work on video which was really helpful for me: https://www.youtube.com/watch?v=kwQk5A26cis&t=822s.

To make this be able to run, you will need to link both the SDL library, and the SDL_Image library. Eventually I will make this into a standalone download, but I believe that I will wait
until I implement an actual artificial intelligence to play against.


## Building
This project use CMake for building.  
You need to install cmake and sdl with sdl-image.  
Then type `cmake .` and you will get .vsproj file/Makefile or XCode project (depending on your OS)  
