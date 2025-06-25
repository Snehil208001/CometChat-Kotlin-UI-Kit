Internship Assignment: CometChat Android UI Kit Integration 🚀
This repository contains an Android application showcasing the integration of CometChat's Android UI Kit, demonstrating real-time messaging and voice/video calling features. This project serves as an internship assignment to evaluate proficiency in Android development and integration of third-party SDKs.

Table of Contents
Features

Prerequisites

Setup Instructions

Usage

Project Structure

License

Features ✨
This project demonstrates a comprehensive set of real-time communication features powered by CometChat's Android UI Kit:

Real-time Messaging 💬

Voice and Video Calling 📞📹

Group Chats 👥

One-on-One Chats 👤

Call Logs 기록

User and Group Management (e.g., blocking users, managing group members, changing user/group scope) ⚙️

Message Features:

Text messages 📝

Image, Video, Audio, and File attachments 🖼️🎥🎵📁

Message reactions 👍❤️

Message editing and deletion ✏️🗑️

Message forwarding and sharing ➡️🔗

Read receipts ✅

Typing indicators ✍️

Mentions @

Link previews 🔗

Message translation 🌐

Extensions:

Polls 📊

Stickers 贴纸

Collaborative Whiteboard and Document 칠판 문서

Smart Replies 💡

AI Conversation Summary 🧠

AI Conversation Starter 🚀

Push Notifications (for Java and Kotlin sample apps) 🔔

Theming and Customization: Extensive customization options for UI elements such as colors, fonts, and component styles. 🎨

Prerequisites 🛠️
To run and build this project, ensure you have the following installed:

Android Studio (latest stable version) 💻

Java Development Kit (JDK 8 or higher) ☕

A CometChat App ID and Auth Key. You can get these from the CometChat Dashboard. 🔑

For push notifications, a Firebase project configured with Google Services. 🔥

Setup Instructions 📋
Clone the Repository:

Bash

git clone https://github.com/cometchat-pro/cometchat-kotlin-ui-kit.git
Open in Android Studio:
Open the cloned project in Android Studio. 📂

Configure CometChat Credentials:

Navigate to the AppCredentials.java or AppCredentials.kt file within the sample-app-java or sample-app-kotlin module (or sample-app-java+push-notification/sample-app-kotlin+push-notification if using push notifications).

Replace the placeholder values for APP_ID, REGION, and AUTH_KEY with your actual CometChat credentials from the CometChat Dashboard. ⚙️

Configure Firebase (for push notifications):

If using the +push-notification sample apps, follow the Firebase setup instructions provided in their respective README.md files.  đẩy

Build and Run:
Sync the Gradle project and run the application on an Android emulator or a physical device. ▶️

Usage 🚀
The application provides a basic chat interface where you can:

Login: Use the provided sample user UIDs (e.g., SUPERHERO1, SUPERHERO2, etc.) to log in and start chatting. 🚪

Chats: View a list of your conversations and start new ones with other users or groups. 💬

Users: Browse a list of available users and initiate one-on-one chats. 🧑‍🤝‍🧑

Groups: View existing groups, join public groups, or create new groups. 🏘️

Calls: Make and receive voice and video calls within chats. 📞

Project Structure 🏗️
The project is structured into multiple modules:

cometchat-uikit-android: This is the core UI Kit library module containing all the reusable UI components and logic for chat features. 📦

sample-app-java: A sample application demonstrating the integration of the UI Kit using Java. ☕

sample-app-kotlin: A sample application demonstrating the integration of the UI Kit using Kotlin. 🧳

sample-app-java+push-notification: A sample application with push notification capabilities using Java. 🔔☕

sample-app-kotlin+push-notification: A sample application with push notification capabilities using Kotlin. 🔔🧳

### Screenshots

![Screenshot of the application](### Screenshots

![image alt](https://github.com/Snehil208001/CometChat-Kotlin-UI-Kit/blob/f840c4a51d67d2868e19f82a7c757e962299a9bb/Screenshot_20250625_172202.png)
