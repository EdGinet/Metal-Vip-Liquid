# Metal Vip Liquid

Welcome to the Metal Vip Liquid game repository! This document will guide you through the installation, gameplay, and development process of this stealth game.

## Type
Stealth game

## Name
Metal Vip Liquid 

## Description

**Metal Vip Liquid** is a stealth game where players must navigate through maps filled with enemies and security cameras. The primary goal is to avoid detection and use weapons found on the map to overcome obstacles and complete mission objectives. Strategic thinking and careful planning are key to success.


## How to Play

- **Navigate carefully** : Avoid cameras and stay out of sight of enemies.
- **Use the weapons** : Find weapons on the map and change them to overcome challenges.
- **Progress Smart** : Plan actions to get around obstacles and achieve your goals.

# Installation

## Prerequisites

Before installing and running the game, make sure you have the following software installed:

- **Java Development Kit (JDK)** 17 or higher.
- **Gradle** version 8.10.2 or higher.
- **LibGDX** library (this is included via Gradle in the project setup).

    
# Setting up the Game

- Clone the Repository:
   To get started, clone this repository to your local machine:
   ```bash
   git clone https://github.com/EpitechMscProPromo2027/T-JAV-501-MAR_13.git

# Execution with Docker

## Prerequisites

To run **Metal Vip Liquid** using Docker Compose, follow these steps.

Docker Compose simplifies the process of building and running the game in a container.

- Make sure you have [Docker](https://www.docker.com/) and [Docker Compose](https://docs.docker.com/compose/install/) installed on your machine.


## Build and start the container using Docker Compose

Run the following command to build the Docker image and start the game in a container:

    docker-compose up --build

**docker-compose up** : Starts the game in the container.

**--build** : This flag ensures that the image is built if it hasn't been built yet or if changes were made.



# Development

## Running Locally

If you want to run the game locally and test changes, follow these steps:

    - Open the project folder in your favorite IDE (e.g., IntelliJ IDEA, Eclipse).

    - Import the project as a Gradle project.
    
    - Build the project using your IDE's Gradle support.
    
    - Run the Main class or use the gradle run command.

## Building the Game

To build the game into a runnable JAR file for distribution:

Run the following Gradle command:

    ./gradlew lwjgl3:dist

After running this command, Gradle will create the .jar file will be located in the lwjgl3/build/libs/ folder.

Run the .jar File with the following command:
    
    java -jar [name_jar_file]
    example : java -jar Metal Vip Liquid-1.0.0 


# Javadoc

For detailed documentation of the project's classes and methods, you can view the Javadoc generated for Metal Vip Liquid here:

https://mohummadpeer.github.io/Metal_Vip_Liquid_Javadoc/
