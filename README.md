# Adesoji Olowa

### Hello, I am an Android developer committed to following best practices for developing insanely performant Android applications and enthusiastic about learning new technologies, methods, and principles as per the project requirements. Keep Learning and Keep Sharing

<a href="mailto:soj.ykn@gmail.com"><img src="https://img.shields.io/badge/Email-adesoji-8056d5.svg?style=for-the-badge&logo=minutemailer&logoColor=white"></a>&nbsp;&nbsp;&nbsp;<a href="https://www.linkedin.com/in/adesoji-olowa/" target="_blank"><img src="https://img.shields.io/badge/linkedin-Adesoji-blue.svg?style=for-the-badge&logo=linkedin&logoColor=white" ></a>&nbsp;&nbsp;&nbsp;<a href="https://github.com/sojious" target="_blank"><img src="https://img.shields.io/badge/github-sojious-red.svg?style=for-the-badge&logo=github&logoColor=white"></a>

# YouHr - Youverify Employee Management tool

This is an HR App developed as an internal tool for [Youverify](https://youverify.co/) to efficiently manage and organize employee-related tasks and information. It provides a user-friendly interface and essential features for handling various HR processes seamlessly. The app constantly communicates with a remote server to fetch employee data (documents, leave history, profile). To ensure a great user experience, it employs an offline-first approach, caching critical data on the device's local storage using the Room Library. The Jetpack Paging 3 library is also used to achieve efficient memory usage.
It has typical Hr features like:
### Features
1. **Authentication:**
   - Employees can log in securely using their passwords and passcodes to access the app. They can also reset their password.

2. **Leave Management:**
   - Employees can request leaves, and HR administrators can review, approve, or reject them through the app.
   - The app also allows employees to check their leave balances and history.

3. **Task Management:**
   - HR administrators can assign tasks to employees, set deadlines, and track their progress through the app.
   - Employees can view their assigned tasks, mark them as completed, and add comments if needed.

4. **Document Upload:**
   - The app enables employees to upload and store important documents securely.
   - HR administrators can manage and organize employee documents efficiently.

5. **Profile Management:**
   - Employees can update and maintain their personal and professional information in their profiles.
   - HR administrators can access and manage employee profiles, ensuring accurate records.


### Technologies Used
- Frontend: Jetpack Compose
- Backend: Node.js
- Database: Room Library
- Networking: Retrofit
- Dependency Injection : Dagger Hilt
- Paging: Jetpack Paging 3 Library
- Architecture: Clean Architecture with MVVM


<p align="center">
<img src="images/youhr_app/youhr-demo.gif" width="250"  title="YouHr Application demo">
</p>

<p align="center">
<img src="images/youhr-app/youhr-frame.png" width="700" title="YouHr frame">
</p>


# Yvos Android Sdk

An Sdk developed for Youverify which enables clients to integrate the company's services into their Android app with minimal effort.
It includes the following identity verification services:

- Identity verification forms that can be filled out by users
- Liveness check functionality
- Document capture functionality

<a href='https://play.google.com/store/apps/details?id=com.jackandphantom.mytodo'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png' height='80px'/></a>

### Technolgies : Kotlin, XML, Jepack Compose, Dokka, MVVM, Retrofit

![Note app feature 1 0](./images/notes_app.gif)


# Stry Application (Educational Application)
<a href='https://play.google.com/store/apps/details?id=alejandro.ibague.studyapp'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png' height='80px'/></a>


This application is still in development and I was on the contract-based android application where I make quizzes, statistics, overlay windows, and fix some errors in different sections of the app.

Application is for the students which contain questions in a quiz wrapped in a package, also the teacher can create packages with number of questions in its answer and those packages will get converted in the quiz and these packages will be available in the packaging market in the application. There are other useful features in application like a floating window where the user can enable and give answers while he is outside of the application and other features like sharing packages and give a review to packages.

### Technolgies : Android SDK , Kotlin, Xml, Firebase, MVVM 

<p align="center">
<img src="images/stry app/Artboard – 1@2x.png" width="700"  title="Stry Application">
</p>

<p align="center">
<img src="images/stry app/stry video.gif" width="190" title="Word Guess">
</p>

# Storyfy Application 
<a href='https://play.google.com/store/apps/details?id=com.harshilzalavadiya.com.storyfy'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png' height='80px'/></a>

When I was working in a company as an intern, I build this application which is basically a storytelling application where you story coming from the server and you can choose your choice in order turn story in your direction.

The application uses firebase to store stories and also it shows different twists according to user choice. It has a quite simple user interface with some animation, the application will upload new stories as they completing writing the stories by writer and the user does not need to update the application in order to read new content. I have used a custom user interface because requirements are to make the app more like a book so we have made the custom drawable and view to perform this action.

### Technolgies : Android SDK , Java, Xml, Firebase

<p align="center">
<img src="images/storyfy app/Artboard – 1@2x.png" width="700"  title="Storyfy Application">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
</p>

<p align="center">
<img src="images/storyfy app/storyfy video.gif" width="210" title="Storyfy">
</p>

# Covid Tracker

I build this application when I was doing a challenge at topcoder where i have APIs for the covid-19 data so this application used to track cases all over the world.
The application uses retrofit, data binding, and Rx java for calling API and fetch all the data in order to show on the list. I used graphs also for indicating the number of cases, deaths, and confirmed cases all over the world. You can also see data particular to a country.

### Technolgies : Android SDK , Kotlin, Xml, RxJava

<p align="center">
<img src="images/Covid app/Artboard – 1@2x.png" width="480"  title="Storyfy Application">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  <img src="images/Covid app/covid video.gif" width="210" title="Storyfy">
</p>


# BeatPlayer Music Application

This is my first application when I was learning android application development, most of the things I implement in the application is custom means I almost try not to use 3rd party libraries because I wanted to learn more deeply about low-level APIs of android.


The application will show you the all the songs which are available in your phone using the content provider and at the same time, it will create the service for the application so that you can easily play the music in the background and I use foreground service with a notification which means you can also listen to your music even if you remove the application from the background. The application also offers you the albums where you have songs according to their albums so you can listen to music based on the albums, also you can search for music in application. It also offers you a good user interface with animation so you will stick to use the application.

### Technolgies : Android SDK , Java, Xml

<p align="center">
<img src="images/Artboard – 1@2x.png" width="1230"  title="Music Application">
</p>



## Thanks for stopping by!
  

   LICENCE
-----

 Copyright 2022 Ankit kumar

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
