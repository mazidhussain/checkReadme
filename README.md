# PW Video Player
A concise yet descriptive project overview.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Tech Stack](#tech-stack)
3. [Prerequisites](#prerequisites)
4. [Getting Started](#getting-started)
5. [Usage](#usage)

## Project Overview <a name="project-overview"></a>
- **Purpose**: 
    - The goal of the PW Video Player project is to provide an efficient and user-friendly video player for educational purposes.
- **Features**: 
    - Key features include seamless video playback, batch assignment functionality, and user-specific customization.
- **Architecture**: 
    - The core technology stack includes React.js, TypeScript, HTML, and CSS. The project is structured to allow easy scalability and maintenance.

## Tech Stack <a name="tech-stack"></a>
List of all technical stack utilized in the project:
- React.js
- TypeScript
- HTML
- CSS
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
    - Install yarn:
      ```bash
      sudo npm install --global yarn
      ```
    - Install dependencies:
      ```bash
      yarn install
      ```
      or
      ```bash
      yarn
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
    ```

The code runs on localhost:3000 but the video player may not be available directly. To check the video player:
Go to the assigned video on the stage server, e.g., https://staging.physicswallah.live/watch/....
Take the URL path from /watch to the end and concatenate it with localhost:3000:
bash
--Copy code
   ```bash
http://localhost:3000/watch/?batchSlug=651d156f851ba2a6e5b45a03&batchSubjectId=651d175963268306bda7da3a&subjectSlug=651d175963268306bda7da3a&topicSlug=all&scheduleId=66711b00b9b063b00dd6f8b4&isUnderMaintenance=false&entryPoint=BATCH_TODAYS_CLASS_VIDEOS_6406edb9dfa3ad00191fe679&learn2Earn=true 
   ```

 - **Open this URL in your browser to access the video player**.
