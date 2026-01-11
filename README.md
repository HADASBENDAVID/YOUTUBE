# YOUTUBE
## *Setting Up the Environment*

### *General Prerequisites*
Before setting up, ensure you have the following installed:
- *Node.js*: Download from [nodejs.org](https://nodejs.org).
- *MongoDB*: Download and install MongoDB from [mongodb.com](https://www.mongodb.com).
- *Visual Studio Code* (or another text editor): [VS Code](https://code.visualstudio.com).
- *Android Studio*: Download from [Android Studio](https://developer.android.com/studio).
- *g++ compiler* (for C++ server).

---

### *Node.js and MongoDB Setup (Backend)*

1.  *Clone the Repository*
     
   git clone https://github.com/HADASBENDAVID/YOUTUBE.git

   cd YOUTUBE

   cd serverApi

     

2. *Install Dependencies*
    
   npm install

   npm install mongoose

   npm install uuid


3. *Initialize Database*

   node addDefaultData.js
     

5. *Create an uploads directory*
   
   cd public
     
   mkdir uploads
     
   cd ..
     

6. *Start the Node.js Server*

   node app.js


---

### *React Frontend Setup*

1. *Navigate to the React project directory:*
   
   cd 'web/src'
   

2. *Install Dependencies*
    
   npm install
     

3. *Start the React Frontend*

   npm start
     

---

### *C++ Server Setup*

1. *Install WSL (Windows Subsystem for Linux)*

   wsl --install
     

2. *Open Visual Studio Code with WSL*
   - Go to the Extensions panel in VS Code and install the *WSL* extension.
   - Open the terminal and connect to WSL:
     
     cd serverCpp
     

3. *Compile and Run the C++ Server*
     
   g++ server.cpp -o server
         
   ./server
     

---

### *Android App Setup*

1. *Navigate to the Android project directory:*

   cd Android


2. *Sync Project with Gradle*

   - Open Android Studio and sync the project with Gradle files.

3. *Run the Android App*

   - Set up an emulator (API 30, Android 11.0 ("R")) for better performance. You can create a new emulator in *Tools > Device Manager > Create Device*.
   - Press the green arrow or use the shortcut *Shift + F10* to run the app.

---



