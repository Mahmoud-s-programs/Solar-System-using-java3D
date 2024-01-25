# Solar System Program

This is a quick guide to help you run the Solar System program on your machine.

## Table of Contents

- [Introduction](#introduction)
- [Setup](#setup)
  - [Java Project](#java-project)
  - [Folder Structure](#folder-structure)
  - [Required Classes](#required-classes)
  - [Java 3D Jars](#java-3d-jars)
- [Usage](#usage)
  - [Keyboard and Mouse Controls](#keyboard-and-mouse-controls)
- [Enabling Orbit Lines](#enabling-orbit-lines)
- [Credits](#credits)

## Introduction

The Solar System program is an interactive simulation of the solar system. It provides information about the planets and allows you to explore the universe.

## Setup

### Java Project

1. Create a new Java project on your machine.

### Folder Structure

Create the following two folders and five classes in your Java project:

- Folder 1: `models` (This folder will contain the texture images and objects)
- Folder 2: `sounds` (This folder will contain the sounds and music used in this project)

Classes:
1. `SolarSystem` - The main class where everything will be run.
2. `SolarSysShapes` - The shapes class.
3. `CommonsMA` - Contains colors and behaviors.
4. `Codes4SS` - This class shows multiple views of the solar system at the same time.
5. `SoundUtilityJOAL` - Contains sound methods.

### Java 3D Jars

Make sure you have the necessary Java 3D jars to run Java 3D programs. You can download and include them in your project.

## Usage

### Keyboard and Mouse Controls

- **X key**: Enable/disable background music.
- **A, S, W, & D keys**: Allow for free navigation inside the universe.
- **Mouse**: Rotate the entire solar system.
- **Click on a planet with the mouse**: A sound will play, providing the planet's name and a fun fact about that planet.

## Enabling Orbit Lines

By default, the orbit lines of the planets are disabled. If you want to see the orbits, uncomment the following line in the code:
```java
//solarSystemTransformGroup.addChild(sceneTGo);

