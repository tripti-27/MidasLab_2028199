# React-Native Maestro Application Setup

## Introduction

This documentation guides you through setting up a React-Native application with Maestro, covering the installation of essential tools, configuration steps, and writing your first Maestro code. Ensure to follow each step for a seamless development environment.

## Prerequisites

Before starting, make sure you have the following installed on your computer:

1. Node.js and npm
2. React Native environment
3. Visual Studio Code (VS Code)
4. Android Studio

## Setup Steps

### Step 1: Setting Up Node.js and npm

1. Install Node.js and npm:
   - Visit the [Node.js official website](https://nodejs.org/).
   - Download and run the installer, following the installation instructions.

2. Verify Installation:
   - Open a terminal or command prompt.
   - Run the following commands to ensure Node.js and npm are installed:
     ```bash
     node -v
     npm -v
     ```
   - You should see version numbers for both.

### Step 2: Setting Up React Native Ignite Environment

1. Install React Native CLI:
   - Open a terminal.
   - Run the following command:
     ```bash
     npm install -g react-native-cli
     npm install -g react-native-ignite
     ```

2. Create Ignite application:
   - Run the following commands:
     ```bash
     Ignite new MyApp
     cd MyApp
     npm start
     ```
   - Check if the output in the simulator matches expectations.

### Step 3: Setting Up Maestro

1. Install WSL2 for Windows:
   - Open a terminal.
   - Run the following command:
     ```bash
     wsl --install
     ```
   - Follow through with instructions and restart the computer.

2. Install JAVA:
   - After restarting, open the Terminal in WSL2 and run:
     ```bash
     sudo apt update
     sudo apt upgrade
     sudo apt install openjdk-11-jdk
     ```

### Step 4: Android Setup in WSL2

- Download Android command line tools from the official site.
- Follow provided instructions to set up Android command lines in WSL2.
- Install basic Android utilities using the provided commands.
- Add necessary environment variables to your `~/.bashrc` file.

### Step 5: Install Maestro and Run First Code

- Install Maestro using the following command:
   ```bash
   curl -Ls "https://get.maestro.mobile.dev" | bash
   ```
- Check your Maestro version using:
   ```bash
   maestro --version
   ```
- Set up ADB and run your first Maestro code. Refer to the [Maestro documentation](https://maestro.mobile.dev/getting-started/run-a-sample-flow) for details.

## Conclusion

Following these steps, you'll have a React-Native Maestro application set up and ready for development. If you encounter any issues, refer to the detailed documentation provided. 

## Contributor
### Name: Tripti Shikha Ojha
### Roll No: 2028199
### Email: triptishikha2002@gmail.com
