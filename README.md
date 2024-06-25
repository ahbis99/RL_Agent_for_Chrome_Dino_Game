# Reinforcement Learning Agent for Chrome Dino Game
This is my project for Reinforcement Learning class that I took in University of Pompeu Fabra. Project created using Python.

## Table of contents
* [General info](#general-info)
* [Environment Info](#environment-info)
* [Technologies](#technologies)
* [Visualization](#visualization)

## General info
The aim of this project is train a Reinforcement Learning Agent which will play epic Chrome Dino game that everybody played at least once in a life. I created a custom Gym environment for the DinoGame, designed for training reinforcement learning agents to conquer the hurdles of this popular offline game and DQN RL agent which trained on this environment.

## Environment Info
* Observation Space: Grayscale image (1, 83,100) representing the game screen.
* Action Space: Discrete actions - 0 for Jump, 1 for Down, and 2 for No action.
* Rewards: +1 for actions Jump, -100 if the game is done, and +3 for No action.
* Rendering: Visual representation using OpenCV.

## Technologies
Project is created with **Python**. The main packages used:

* gym, gymnasium (Environment)
* Numpy (Matrix operations)
* Matplotlib (Data visualization)
* OpenCV (Picture manipulation)
* Pytesseract (Image to string, OCR)
* PyautoGUI (Keyboard inputs)

## Visualization
Picture manipulation from raw input to the desired form. Black and white picture shows raw input other picture shows last form of the picture which used while training the model.

<img width="501" alt="Ekran Resmi 2024-06-25 13 28 33" src="https://github.com/ahbis99/RL_Agent_for_Chrome_Dino_Game/assets/76615322/0e0f8493-463e-4a97-9d38-2f351cbba94a">
