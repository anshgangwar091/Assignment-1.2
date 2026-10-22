Step 1: Install Visual Studio Code
Go to code.visualstudio.com and download the installer for your operating system (Windows, macOS, or Linux).

Run the downloaded setup file and follow the installation instructions.

Step 2: Install the LTS Version of Node.js
Go to nodejs.org.

Click the download button for the LTS (Long Term Support) version.

Open the installer and proceed with the default setup options.

Step 3: Install VS Code Extensions
Open Visual Studio Code.

Click the Extensions icon on the left sidebar (or press Ctrl + Shift + X on Windows / Cmd + Shift + X on Mac).

Search for Live Server (by Ritwick Dey) and click Install.

Search for Prettier - Code formatter (by Prettier) and click Install.

Step 4 & 5: Create Project Folder and Files
Open your terminal or file explorer and create a folder named web-development-practice.

Open VS Code, go to File > Open Folder..., and select the web-development-practice folder.

Inside this folder, create three new files:

index.html

style.css

script.js

Step 6: Run HTML in Browser with Live Server
Open index.html in VS Code.

Right-click anywhere in the editor and click "Open with Live Server" (or click the "Go Live" button at the bottom right status bar).

Your default web browser will automatically open and display your web page at [http://127.0.0.1:5500/index.html](http://127.0.0.1:5500/index.html).

Step 7: Verify Node.js & npm Installation
Open the terminal inside VS Code by pressing Ctrl + `  (or going to Terminal > New Terminal).

Run the following command to check the Node.js version:
node -v

Run the following command to check the npm version:
npm -v