# OpenPlayer

OpenPlayer is an open-source android media player for music, videos, and audio books. OpenPlayer is free from advertisements, micro transactions, subscriptions, and mega corporations. OpenPlayer does not collect, store, or sell ANY user data, and does not require any active internet connection to use. OpenPlayer only needs an internet connection when opening outside links, such as to this GitHub repository or when checking for updates with the Google Play Store.


## Who?

Hello, My name is Zackery Fleming, I am a semi recent (at least in summer of 2025) college graduate with a degree in software development. I also have backgrounds in database management, networking, and Cybersecurity.

I develop various projects, which can be seen in my GitHub repositories. I hold the open-source community highly, and believe in things like user serviceability and user control over their hardware and software.


## What?

AS stated above, OpenPlayer is an open-source media player for Android. OpenPlayer uses API 24, or Android 7.0 "Nougat". This will allow approximately 98.5% of all Android devices to run OpenPlayer. Perhaps later, I can port the project to an older version of the API, so more devices can use OpenPlayer.

Currently, there are no plans for developing an IOS version of this application, as the time and monetary investment to develop an IOS app are too high for me. This is a passion project that I am developing in my free time.

However, since this is an open-source project, anyone can port the project to IOS or any other platform as they wish (with proper attributions and copy right notices, according to the GNU General Purpose License terms).


## Why?

This project started due to a few reasons: 

1. My increasing concern and awareness with the amount of data companies collect and use from their users
2. My belief that users should have more control over the software and hardware they purchase
3. Some applications with egregious monetization methods
4. I am a maker

### Data Collection and Privacy

First, is my increased concern with the increasing amount of user data that large companies collect, store, and sell. While some data collection is required (for instance for account creation, or user metrics), companies don't need to collect every possible piece of information on their users. 

I have been thinking more about what info various companies have on me, and if I can truly trust them with it. While I know that security and privacy is not impenetrable; I do know that some companies put more effort into data protection and privacy than others.

With that said, OpenPlayer does not collect, store, or sell any user data. The only thing OpenPlayer keeps track of, is the number of times each media is played. This is to create the most and least played playlists. More info can be found in the [privacy policy](https://github.com/Zack-Fleming/OpenPlayer/blob/master/PRIVACY.md).

### User Control of Software

When it comes to user control in software, most software gives minimal control over the software. While this limited control is to avoid the issues that would be created from letting users change software to their wants. The open-source nature of OpenPlayer lets users make a copy of the software with any edits they wish to make. 

OpenPlayer's open-source nature will also allows users to see that the developer, i.e. me, or contributors have not hidden features with potentially nefarious purposes. Think of software or games that were found to hide Bitcoin mining software within itself. 

Also, OpenPlayer also contains many customization for the GUI elements. Users will be able to change the majority of UI elements, from the color, font, and size of text, listing styles of media, and the used icons and images of the application as well. 

### Monetization

I will preference this section with this: 'developers should be paid for their work'. The issue I have with the monetization of software, is when its in the face of users. For example, a mobile game I used to play showed the user fifteen to twenty micro transaction popups, every time the game was launched. If a game is going to do that, show the popup once to the user, they know where the in-game shop is. 

Also on the topic of monetization, advertisements in software and websites are becoming more prevalent. While putting ads into software is not inherently bad, the ads are not the focal point of the software. Think of articles on websites that are more ads than article text. Another mobile game I used to play started out just showing an add for doubling my offline rewards or periodic additional rewards. When I stopped playing the game, ads accounted for around 40% of the time I was playing the game. Having ads to this degree is too much. 

Additionally, if a dev or company wants that many ads, at least give the user a choice of if they want to watch the ad or not. The aforementioned game, did include buttons to watch and not watch the ad. However, when I clicked the button to skip the ad, it would still play an ad, just a slightly shorter one instead of a full length ad.

### I Just Like to Make Things

The last main reason for making this project is, I am drawn to the DIY. Most of the projects I have done for software and hardware development, is just because I like to learn and create things. I like to challenge myself by learning new things and solving problems. I also like using software and hardware that allows users to just create (such as the Arduino, Raspberry PI, ESP32, open-source, etc.).

Creating OpenPlayer lets me learn more about mobile development (Kotlin). Also, I can make software with the feature I would like to see from similar software. While most of the features I will develop are the same as any other media player, some of the planned features are not from many or any media player I have used (if they are, I have not used them all).


## Where?

OpenPlayer will be distributed on the Google Play Store and here in the GitHub releases. The application will have a button/link to check for updates, either on the Play Store or on GitHub. Just choose the link from where you originally downloaded the app from.

Updating from the Play Store is as easy as either clicking the 'Check for Play Store Update' button, which brings you to the Play Store page. Or, set the Play Store to automatically update the app, when one is uploaded.

Updating the app from GitHub releases, you will have to uninstall the old version and install the new one (a workaround will be found as apart of my road map for the app). I will implement a way to export and import user settings. These settings will include any playlists, customization, and other edits the user has made to the default application.


## Main Features

Below is a list of the currently implemented features. The features are split into the following categories: audio, video, audio book, and customization.

A to-do list of the tasks being worked on can be found on [YouTrack - OpenPlayer Development](https://openplayer.youtrack.cloud/agiles/194-1/current).

A gantt chart showing the same tasks, but with their estimated time-to-completion can be found on [YouTrack - OpenPlayer Gantt](https://openplayer.youtrack.cloud/gantt-charts/212-1).

**Note: the to-do board and gantt chart 'should' be setup where anyone can publicly view them (I hold the edit permissions). If you cannot view them, email me so I can fix it.**

### Version Numbers

I will take a bit of time to mention how the version numbers for OpenPlayer work. The version number has three parts: major version, minor version, and build number. The major version is the number of completed organizers on the gantt chart. The minor version is the number of tasks that have been completed, within an organizer. The build number is the number of times the project has been built between minor versions.

For example, if i am on the third card under the fourth organizer, and have built the project fifteen times, the version number would be 4.3 build 15, or 4.3b15, or 4.3.15b.

For the changelog and releases, I will use the last listed option of: \<major\>.\<minor\>.\<build\>b.

### Audio

*There are currently no features added here yet, the project is still being setup*

### Video

*There are currently no features added here yet, the project is still being setup*

### Audio Book

*There are currently no features added here yet, the project is still being setup*

### Customization

*There are currently no features added here yet, the project is still being setup*
