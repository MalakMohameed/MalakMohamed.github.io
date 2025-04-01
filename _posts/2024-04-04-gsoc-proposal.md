---
title: My Proposal For Google Summer Of Code 2024
author: amr
date: 2024-04-04 00:00:00 +0800
categories: [GSoC]
tags: [Open Source,Android]
render_with_liquid: false
image:
  path: /assets/gsoc.png

---


## Project Description


**Name:**  [**OBA Android App - Build Surveys into OneBusAway**](https://opentransitsoftwarefoundation.org/2024/01/google-summer-of-code-2024-projects/)

**Mentors:**
  - Aaron Brethorst, Executive Director, OTSF (US/Pacific Time) 
  - Kari Watkins, Board Chair, OTSF (US/Pacific Time)

**Goal:** The primary goal for integrating short travel survey functionality into the OneBusAway app enable riders to rate aspects of service or answer questions about improving their transit experience. This feature aims to assist transit agencies in better understanding their riders' needs, thereby enhancing the overall quality and accessibility of transit services. It specifically seeks to support research efforts that examine the impacts of real-time traveler information on transit customers' attitudes and behaviors with an immediate focus on addressing and better serving women’s unique travel experiences, including mobility of care trips and complex travel patterns.

## About Me


- **Email:** [amrhossam.dev@gmail.com](mailto:amrhossam.dev@gmail.com) 
- **Country:** Egypt
- **LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/amrhossamdev)  
- **GitHub:** [GitHub Profile](https://github.com/amrhossamdev)  
- **Google Play:** [Developer Page](https://play.google.com/store/apps/dev?id=7508009697443715929&hl=en_US)  


I am Amr Hossam, a senior computer science student at Damanhour University in Egypt. I have been an Android enthusiast for more than eight years. My journey began with installing custom ROMs on my old Android phones, editing ROMs, and customizing the UI for Android. This experience has given me a deep understanding of Android and has helped me gain profound insights into Android development.

I have been interested in developing Android apps that support the community. I developed an app to guide people on how to start learning programming and the app reached more than **100K downloads** in the Play Store and more than **+1700 rates.** [Play Store](https://play.google.com/store/apps/details?id=com.amrhossam.msarmobarmg\&hl=en_US).

Also, I have worked to develop an entire Android app that serves more than **+25K daily users** in real-time, the app was responsible for displaying the price of the dollar in more than 28 banks at the same moment It also displays the price of the Egyptian-pound against 20 different currencies, the app exceeded more than **600K downloads** and **+4000 rates** in the [Play Store](https://play.google.com/store/apps/details?id=emexp.dollarprice.free\&hl=en_US).

Besides that, I'm interested in competitive programming. I reached the finals in my region **ACPC** (The Africa and Arab Collegiate Programming Championship), which gave me a solid understanding and knowledge about data structures & algorithms that helped me care about app performance and have a deep understanding of code time and space complexity.

I have always had a passion for open source so **GSoc** is a golden opportunity for me to show my skills and make an impact on people's lives by working on the **OneBusAway** application, I have been reviewing users' tweets/reviews in Google Play and X platform about the app, I found that the app has fans and a lot of users depends on it, this makes me more and more excited to make an impact!

## Investigations

- [x] **Build the project:** Set up and configure the development environment and dependencies in Android Studio to build OneBusAway

- [x] **Intend to familiarize myself with the codebase.:** In the last few weeks, I've spent much time learning about the project. I looked carefully at the code, figuring out how it was organized and finding the main parts. I also delved into how the project works, seeing how different pieces fit together

- [x] **Started contributing to familiarize myself more:** I identified issues affecting the app's user experience. I opened multiple [issues](https://github.com/OneBusAway/onebusaway-android/issues?q=is%3Aissue+author%3Aamrhossamdev+is%3Aclosed) and fixed them. Additionally, I addressed numerous bugs that impact user experience, and I tackled these bugs from the [issues](https://github.com/OneBusAway/onebusaway-android/issues) section. and worked on adding enhancements to the OneBusAway app

- [ ] **Build Surveys into OneBusAway Feature:** Currently, I’m trying to learn more about the build surveys feature, i will be discussing it with the mentor to make sure I understand everything about this feature and all the technical details and user flow and also with backend team to understand more about the service that will work for the survey

- [ ] **Understanding Qualtrics SDK:** I will start to familiarize myself with the Qualtrics SDK, which will be used in building the surveys feature



## Contributions List

I worked on 15 issues and enhancements that have been **merged** into the main codebase.


| PR Number | Title/Description | Date | Status | Comments/Type |
|-----------|-------------------|------|--------|---------------|
| [#1120](https://github.com/OneBusAway/onebusaway-android/pull/1120) | Add dialog text for HTML Parsing | 2024/2/25 | Merged | UI Enh. |
| [#1128](https://github.com/OneBusAway/onebusaway-android/pull/1128) | Correct button spacing on home screen | 2024/2/29 | Merged | UI Enh. |
| [#1129](https://github.com/OneBusAway/onebusaway-android/pull/1129) | Fix vehicle marker arrow overlap | 2024/2/29 | Merged | UI Enh. |
| [#1130-#1143](https://github.com/OneBusAway/onebusaway-android/pull/1130) | Map style update: No POI, dark mode | 2024/2/29 | Merged | UI Enh. |
| [#1125](https://github.com/OneBusAway/onebusaway-android/pull/1125) | Localhost IP fix for emulator testing | 2024/2/26 | Merged | Enh. |
| [#1135-#1166](https://github.com/OneBusAway/onebusaway-android/pull/1135) | Trip Planner bug fix | 2024/3/1 & 3/12 | Merged | Bug Fix |
| [#1156](https://github.com/OneBusAway/onebusaway-android/pull/1156) | Google Maps info dialog glitch fix | 2024/3/10 | Merged | Bug Fix |
| [#1159](https://github.com/OneBusAway/onebusaway-android/pull/1159) | Arrival dialog crash fix | 2024/3/10 | Merged | Bug Fix |
| [#1164](https://github.com/OneBusAway/onebusaway-android/pull/1164) | Backup restore crash fix | 2024/3/11 | Merged | Bug Fix |
| [#1175](https://github.com/OneBusAway/onebusaway-android/pull/1175) | Enable route saving on local devices | 2024/3/9 | Merged | Feature/Enh. |
| [#1174](https://github.com/OneBusAway/onebusaway-android/pull/1174) | Weather overlay feature via OBA API | 2024/3/14 | Merged | Feature/Enh. |
| [#1181](https://github.com/OneBusAway/onebusaway-android/pull/1181) | Dark mode for TimeDatePicker dialog | 2024/3/17 | Merged | UI Enh. |
| [#1182](https://github.com/OneBusAway/onebusaway-android/pull/1182) | Deep-link support for custom regions | 2024/3/19 | Merged | Feature/Enh. |
| [Issue #1054](https://github.com/OneBusAway/onebusaway-android/issues/1054) | OBA API issue investigation and fix | 2024/2/27 | Open Issue | Investigation |



These **contributions** helped to get me familiarized with the codebase. I also tried different things like calling OBA APIs (I worked on this when I was adding the weather overlay feature), getting familiar with a lot of app parts like UI, network architecture, local DB design, how the map works, will help me for sure to work on **Build Surveys into OneBusAway Feature.** And getting finalized more with the code base and the app architecture.



## Detailed Design

### Retrieving and Processing Study Participation Requests (SPRs): 

- The app will make HTTP GET requests to the specified API endpoint (https\://onebusaway.co/api/v1/regions/:region\_identifier/study\_participation\_requests.json) to fetch SPRs. 

- Upon retrieval, the app will filter out SPRs the user has dismissed or responded to.

- The remaining SPRs will be processed and displayed within the app's user interface.


### Actions Triggered by Tapping the Call-to-Action:

- We first check if we have runtime permissions to send users notifications. This information can be found in the [Android docs](https://developer.android.com/develop/ui/views/notifications/notification-permission)

- In this context, one possible solution is to utilize the FCM (Firebase Cloud Messaging) token obtained from the user's device to facilitate push notifications. 

- FCM token will then enroll the user into the study to receive surveys.

- I will be using Java Class UUID to create UUID which will be a unique identifier for the user


```java
String uuid = UUID.randomUUID().toString();
```

### Enrolling users to Receive Notifications:

- I will be using the user FCM token to enroll the user when he responds to the call to action

- There are a lot of test cases to cover in this case if the FCM token is expired so we will need a service for sure to update the FCM token for the user.

- One possible solution is to apply the best practices for using FCM tokens [Click here](https://firebase.google.com/docs/cloud-messaging/manage-tokens)### Ui settings:- One possible solution for storing the notification state is to use SharedPreferences to save the notification state in the user's device and I will be checking if the user opted to receive notifications or not before triggering it.

- Decide on an appropriate local storage solution (e.g., SQLite database, Room, shared preferences) for persisting SPRs, user responses, and other necessary data.

- Implement functionality to send HTTP DELETE requests to leave a study, handling this through the user interface.### Testing and Quality Assurance:- Unit and Integration Tests: Write extensive unit and integration tests covering the logic for fetching, filtering, and displaying SPRs, as well as user interactions.

-  UI Tests: Implement UI tests (e.g., using Espresso) to verify the user experience and interactions with the SPR UI components.

## Implementation Plan

#### Understand more about the functional requirements 

- I will be focusing on gaining a thorough understanding of the functional requirements for the Build Surveys into OneBusAway feature. I will discuss more with my mentor to clarify any uncertainties and gather all the necessary information. 

- Proceed with the implementation phase with a clear understanding of the desired outcomes.

#### Planning the implementation details in detail

- After gathering all the necessary ideas and information, I will begin with the implementation details and design a comprehensive mock-up that visualizes the feature accurately. 

- I Will work on a mock-up that will represent the feature's functionality and user interface, helping to ensure that all aspects are well-conceived and user-friendly. I will use tools like [Figma](https://www.figma.com/) or I will be writing the prototype using Android UI.

#### UI development for SPR display 

- After discussing the build surveys feature's technical details and user flow with the mentor, I will begin developing the UI. I aim to create a user-friendly and intuitive interface that seamlessly integrates with the Qualtrics SDK and the backend service.

- I will ensure that the UI is aligned with the overall design aesthetic of the OneBusAway app.

#### Qualtrics SDK integration and survey participation flow

- Familiarize myself with Qualtrics Android SDK

- Integrating Qualtircs SDK to OneBusAway Android App

- Developing user notification logic that will be responsible for enrolling users to study to receive the surveys

- Testing the survey flow after integrating with Qualtrics.

#### Integrating OBA Backend Service

- Work to implement the OBA survey feature APIs

- Connecting the service to the UI elements 

- Testing the survey flow after integrating with the backend.

#### Develop SPR management settings


- Implement the logic for managing SPR data within the app.

- Develop mechanisms for storing, retrieving, and filtering SPR data

- Code the functionality to dismiss and track responded SPRs.

- Testing the survey flow after integrating with Qualtrics.

#### Testing and finalizing the feature

- Make sure to fully the feature and it’s production ready

- Write documentation for the feature. I will include it in the PR

- Check the code thoroughly and make any needed improvements. After that, submit the final project.

## Proposal Timeline


| Period                        | Work                                                                                                                                                    |
|-------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|
| First 3 weeks - May (1 - 26) | Engage in communication with the mentor to thoroughly discuss the project. As mentioned in step (1) of the plan, I will also start in step (2).    |
| Week 4 (Coding officially begins) | I will be finishing step (2) and gathering feedback on it, and I will start to work on step (3).                                                |
| Week 5                        | Finish step (3) and start to work on step (4).                                                                                                           |
| Week 6                        | Finish step (4) and start to work on step (5).                                                                                                           |
| Week 7                        | Start to work on step (6) and roll out the feature for testing purposes to gather feedback.                                                             |
| Week 8                        | - Ensure the feature is fully developed and ready for production step (7). <br>- Write documentation to accompany the feature, which will be included in the pull request (PR). <br>- Conduct a thorough code review and implement any necessary improvements before submitting the final project. |
| Week 9                        | Leaving this week for unexpected things and I will also be using this week to fully test the feature.                                                  |
| Week 10 - (Final Week)       | - Conduct a comprehensive review of the code to ensure adherence to coding standards and evaluate its overall quality. <br>- Submitting a final work.  |


## Why me

I love Android and have been tinkering with it for years. I've built apps that people use, and I know how to make them work well. I'm not just about coding; I care about making apps that people enjoy using. I'm already diving into the OneBusAway project, finding and fixing problems to make the app better. With me on board, you'll get someone who's passionate, experienced, and ready to make a real difference.

