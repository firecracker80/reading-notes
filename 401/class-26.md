# Reading Assignment 26

## Application Fundamentals
>
>The languages Kotlin, Java, and C++ can all be used to create Android apps. An APK or Android App Bundle >is created using the Android SDK tools by compiling your code together with any data and resource files.
>
>Android-powered devices use an Android package, which is an archive file with an.apk suffix, to install >apps. An Android package contains the contents of an Android app that are needed during runtime.
>
>The contents of an Android app project are included in an archive file with the.aab suffix called a "Android App Bundle," along with some extra metadata that is not needed during runtime.
>
>The following Android security features safeguard each Android app in its own security sandbox:
> - Android operating system, a multiuser Linux system.
> - A unique Linux user ID, used only by the system and unknown to the app.
> - Its own virtual machine, which runs the isolated code.
> - Its own Linux process, launching the process whenever one of the app's components has to be run and terminates it when it is no longer required or when the system needs to free up memory for other apps.
>
>## App Components
>
>*Activities*: the first step in communicating with a user is to engage them in an activity. It represents a single user interface screen. The following crucial interactions between a system and an app are facilitated by an activity:
> - Keeping track of what the user currently cares about.
> - Knowing that previously used processes contain things the user may return to.
> - Helping the app handle having its process killed so the user can return to activities with their previous state restored.
> - Providing a way for apps to implement user flows between each other, and for the system to coordinate these flows.
><!-- Retrieved from developer.android.com. -->
>
>*Services*: an all-purpose entry point for running an app in the background for many purposes. It is a component that works behind the scenes to carry out lengthy tasks or work on behalf of remote processes. There is no user interface offered by a service.
> - Started services - tell the system to keep them active until all of their work has been done.
>     - Music playback - the user is clearly aware of this process.
>     - Regular background service - the user is not directly aware, giving the system more freedom to manage the process.
> - Bound services - it runs because another app or process is using its API.
>
>*Broadcast Receivers*: an element that allows the system to send events to the app outside of a typical user flow, enabling the app to react to system-wide broadcast messages. Because broadcast receivers are another clearly defined entry into the app, the system is able to distribute broadcasts to apps that aren't actively functioning.
>
>*Content Providers*: controls a shared collection of app data that can be stored in the file system, a SQLite database, online, or in any other persistent storage space that your program is able to access. If the content provider permits it, other apps may query or alter the data through the content provider.
>
>## Activating Components
>
>Activites, services, and broadcast receivers are activated using *intents*, an asynchronous message. The result of any requested activity is also returned in an intent. Content providers are activated by a targeted request from a content resolver.
>
>## The Manifest File
>
>The Android system must read the app's manifest file, AndroidManifest.xml, in order to recognize an app >component before starting it. This file, which must be located at the top of the app project directory, >must list every component that your app contains.
>
>In addition to listing the components of the app, the manifest also performs a variety of other tasks, >such as the following:
> - Identifies any user permissions the app requires.
> - Declares the minimum API Level required by the app, based on which APIs the app uses.
> - Declares hardware and software features used or required by the app, such as a camera, bluetooth services, or a multitouch screen.
> - Declares API libraries the app needs to be linked against (other than the Android framework APIs), such as the Google Maps library.
><!-- Retrieved from developer.android.com -->

## Things I want to know more about...
>The section on content providers caught my atttention, because of how other app processes are accessed for their API. It makes it appear as if it were part of the app in use, when in actuality it's not.