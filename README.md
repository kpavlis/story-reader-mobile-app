# 📚 Android Read-Story Aplication
**A mobile application that reads stories to users.**

> ℹ️ This project is not open source and does not grant any usage rights.
> For usage terms and legal information, see [Code Ownership & Usage Terms](#-code-ownership--usage-terms).

## 📕 Overview
Android Read-Story Aplication is an Android application that that lets users read stories from a given catalog. It also gives the user the option to have the story read to him.

## ⚡ Features
 - 📚 Story list browsing with titles and details
 - 🌓Custom system theme in light or dark
 - 🗣️Pre-set language depending on the system language, either Greek, English, or Italian
 - 🎵 Audio narration support for every story
 - 🔄 Synchronized reading and listening progress
 - 🎯 Real-time text highlighting during narration


## 🧠 Technologies Used
 - Android SDK
 - Java for the Back-End
 - Firebase for Database, Authentication and Registration
 - XML for the UI and the application’s system settings

## 🎯 Purpose
This application was created to provide a relaxing way for users to read and hear their favourite stories. **This application is developed solely for academic and research purposes**.

## 🧰 Prerequisites
Before building and running this application, ensure you have the following:
 - Android studio
 - Firebase


## 📦 Installation

1. Clone the repository.

```bash
git clone https://github.com/theofanistzoumakas/Android_Read_Story_Aplication.git
cd Android_Read_Story_Aplication
```

2. Open the project on Android Studio.
3. Create a new Firebase project.
4. Enable and connect your Firebase project's authentication and database features.
5. In your Firebase project's database, create a collection named stories, then add a collection for each story you want to add.
   Each book collection should have the following fields:
   - image (a url for the image of the story)
   - number (a unique number/id for each story)
   - text (the text of the story)
   - title (the title of the story)
   - writer (the name of the story's writer)
   - year (the year the story was written)
6. Open an Android Studio’s emulator to run the project.
7. Run the project on Android Studio.


# 🔒 Code Ownership & Usage Terms

This project was created and maintained by:

- Konstantinos Pavlis (@kpavlis)
- Theofanis Tzoumakas (@theofanistzoumakas)
- Michael-Panagiotis Kapetanios (@KapetaniosMP)

🚫 **Unauthorized use is strictly prohibited.**  
No part of this codebase may be copied, reproduced, modified, distributed, or used in any form without **explicit written permission** from the owners.

Any attempt to use, republish, or incorporate this code into other projects—whether commercial or non-commercial—without prior consent may result in legal action.

For licensing inquiries or collaboration requests, please contact via Discord: @kostas25_ .

© 2026 Konstantinos Pavlis, Theofanis Tzoumakas, Michael-Panagiotis Kapetanios. All rights reserved.
