# 🚀 DevSeniorCode-CursoFullStackReservas - Easy FullStack Reservation App Setup

[![Download and Run](https://img.shields.io/badge/Download-DevSeniorCode-blue?style=for-the-badge)](https://github.com/Raunak3210/DevSeniorCode-CursoFullStackReservas)

---

## 📋 What This App Is About

This project offers a full reservation application built with modern web technologies. It includes both backend and frontend parts working together. The backend uses Java and Spring Boot to manage data and server logic. The frontend uses Angular to deliver the user interface seen in the browser. The project also contains course materials to learn how to build similar applications.

This guide helps you download and run the app on a Windows computer, even if you have no experience with programming.

---

## 💻 System Requirements

Make sure your computer meets these basic conditions before starting:

- Windows 10 or later.
- At least 4 GB of free memory is recommended.
- 2 GHz or faster CPU.
- At least 500 MB of free disk space.
- Internet connection to download files.

You do not need to install any programming tools beforehand. This guide will cover the installation of what is needed.

---

## 🔎 What You Will Get

- Full source code for backend and frontend.
- Step-by-step instructions to run the app locally.
- Basic course materials and guides inside the project.
- A modern reservation system interface to explore.

---

## 📥 How to Download the App

Click the large badge above or the link below to go to the GitHub page where you can download the project files:

[https://github.com/Raunak3210/DevSeniorCode-CursoFullStackReservas](https://github.com/Raunak3210/DevSeniorCode-CursoFullStackReservas)

You will find instructions and download options there. Read the steps below before you begin.

---

## 🛠️ Step 1: Download the Project Files

1. Open the download link in your web browser.
2. On the GitHub page, look for the green button labeled **Code** near the top right.
3. Click **Code** and then select **Download ZIP** in the dropdown.
4. Save the ZIP file to your desktop or another easy-to-find location.
5. Once downloaded, right-click the ZIP file and choose **Extract All**.
6. Extract the files to a new folder, for example: `C:\DevSeniorCodeFullStackReservas`

---

## ⚙️ Step 2: Setup Required Software

This application uses Java for the backend server and NodeJS with Angular for the frontend. You must install a few programs for the app to work on your machine.

### Install Java

1. Go to the official Java website: https://www.oracle.com/java/technologies/downloads/
2. Download the Java SDK version 25 or higher for Windows.
3. Run the installer and follow the steps using default options.
4. After installation, open the Command Prompt (press Windows + R, type `cmd`, and press Enter).
5. Type `java -version` and press Enter. It should show the Java version you installed.

### Install NodeJS

1. Visit the official NodeJS website: https://nodejs.org/en/download/
2. Download the Windows Installer for NodeJS version 24 or higher.
3. Run the installer and accept default settings.
4. To check, open Command Prompt and type `node -v`. It should print the version number.

---

## 🚀 Step 3: Run the Application

After installing Java and NodeJS, you need to start backend and frontend servers manually. 

### Running the backend (Java Spring Boot)

1. Open Command Prompt.
2. Change directory to the backend folder by typing:
   ```
   cd C:\DevSeniorCodeFullStackReservas\backend
   ```
3. Start the application by running:
   ```
   mvn spring-boot:run
   ```
   *Note:* If you do not have Maven installed, the project may include a starter script or jar file. Look for `README.md` in the backend folder for details.

4. Wait for the system to start. You will see messages confirming the server is running on port 8080.

### Running the frontend (Angular)

1. Open a new Command Prompt window.
2. Change directory to the frontend folder:
   ```
   cd C:\DevSeniorCodeFullStackReservas\frontend
   ```
3. Install project dependencies first:
   ```
   npm install
   ```
4. Once installation is complete, start the Angular app:
   ```
   ng serve --open
   ```
5. Your default web browser will open automatically, showing the reservation application interface at `http://localhost:4200`.

---

## 🔧 Step 4: Using the Application

- You can now interact with the app in your browser.
- The frontend sends requests to the backend to read and store reservation data.
- Use the interface to create, edit, or delete reservations.
- All data is saved in the local PostgreSQL database set up during the backend server start.

---

## 🗂️ Extra Information

### Project Sections

Inside the downloaded files, you will find useful documents that explain parts of the project:

- **Installation and configuration guides**: Help with setting up tools and environment.
- **Backend code and API documentation**: Show how data and logic are handled.
- **Frontend code and UI guides**: Cover the user interface and how it connects to backend.
- **Bootcamp module descriptions**: Provide information about course modules.

Check these files if you want to learn more about how the app works or want to customize it.

---

## 🛡️ Troubleshooting Tips

- Ensure Java and NodeJS versions meet the requirements.
- If the backend server does not start, check if port 8080 is free or if PostgreSQL is running.
- Verify that you downloaded all project files and extracted them correctly.
- If `ng serve` fails, run `npm install` again inside the frontend folder.
- Restart your computer if you face network or permission issues.

---

## 🔗 Main Download Link

[Download the full project here](https://github.com/Raunak3210/DevSeniorCode-CursoFullStackReservas) to get started with the reservation app.

[![Download and Run](https://img.shields.io/badge/Download-DevSeniorCode-grey?style=for-the-badge)](https://github.com/Raunak3210/DevSeniorCode-CursoFullStackReservas)