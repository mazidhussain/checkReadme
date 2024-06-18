# PW Video Player
A concise yet descriptive project overview.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Tech Stack](#tech-stack)
3. [Prerequisites](#prerequisites)
4. [Getting Started](#getting-started)
5. [Usage](#usage)
6. [Testing](#testing)
7. [Deployments](#deployments)
8. [Contributors](#contributors)
9. [License](#license)

## Project Overview <a name="project-overview"></a>
- **Purpose**: 
    - The goal of the PW Video Player project is to provide an efficient and user-friendly video player for educational purposes.
- **Features**: 
    - Key features include seamless video playback, batch assignment functionality, and user-specific customization.
- **Architecture**: 
    - The core technology stack includes Node.js and Yarn for managing dependencies and running the application. The project is structured to allow easy scalability and maintenance.

## Tech Stack <a name="tech-stack"></a>
List of all technical stack utilized in the project:
- Node.js v16
- Yarn

## Prerequisites <a name="prerequisites"></a>
Before you begin, ensure you have the following dependencies installed:
- Node.js v16
- Yarn

## Getting Started <a name="getting-started"></a>
Follow these steps to get the project up and running:
- **Installation**: 
    - Clone the project: 
      ```bash
      git clone https://gitlab.com/penpencil-services/uxcc/pw-video-player.git
      ```
    - Navigate to the project directory:
      ```bash
      cd pw-video-player
      ```
    - Install dependencies:
      ```bash
      yarn install
      ```
- **Configuration**: 
    - Open the project in VS Code and locate the `creds.json` file.
    - Initially, this file has empty values. You need to get the necessary credentials from the QA team.
- **Initialization**: 
    - Ask QA to assign any batch on the server stage.
    - Go to the stage server, find the token, user, and randomId values from the application/localhost of stage, and copy these values into the `creds.json` file.

## Usage <a name="usage"></a>
- Run the application:
  ```bash
  yarn start
