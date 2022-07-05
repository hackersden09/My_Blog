---
layout: default
---

## How to understand the Android Architecture


# Android Architecture

Android architecture contains different number of components to support any android device needs. Android software contains an open-source Linux Kernel having collection of number of C/C++ libraries which are exposed through an application framework services.

Among all the components Linux Kernel provides main functionality of operating system functions to smartphones and Dalvik Virtual Machine (DVM) provide platform for running an android application.

The main components of android architecture are following:-

    Applications
    Application Framework
    Android Runtime
    Platform Libraries
    Linux Kernel

![Thumbnail of Hacker](./Android-system-architecture)

# Application Layer

It is the part of “Application”, each “Application” developed to be installed and run, such as the program “Facebook” or “Line”, which “Application” has an extension of “.apk”, which when installed successfully. and it will be in the folder “/data/app” and the data section of “Application” is located at “/data/data”.

# Application Framework Layer

It is part of the “System API” (Application Programming Interface) that the “Application” developed and installed can run. where the “Application Framework” section will facilitate developers. “Application” does not require complicated additional programming. but can be executed via “API” immediately, which can be divided as follows

![Thumbnail of Hacker](./Android-system-architecture2)


    Activities Manager “API” for managing “Activity” or per-user display.
    Content Provider “API” for managing access to data from other programs suitable for sharing data between “Application”
    View System “APIs” for managing structures or user interface components (Controls) such as “button” “text box” or “web browser” in conjunction with Activities Manager.
    Telephony Manager “API” manages access to phone data.
    The Resource Manager “API” handles other non-programming information. (Programming) “strings” “layout” screen, which is located in the “res/” directory.
    Location Manager “API” manages the geographic location of the “Android” device.
    Notification Manager “API” deals with events that happen to the “Android” device and then displays the results to the user, such as “Miss call”.

# Libraries Layer
It is part of the “C” and “C++” libraries at the “low-level process” level, for example: 

    Surface Manager is a library for drawing screens. or display
    The Media Framework is a multimedia library for images, video, and audio.
    SQLite is a small library for working with “SQLite” data. We can store various information of “Application” in this database.
    Open GL | ES is a library for 2 or 3D images.
    FreeType is a library for rendering both “Bitmap” and “Vector” images.
    WebKit is a library for displaying web browsers. You can learn more at https://developer.android.com/reference/android/webkit/package-summary.html
    libc is a library of the "C" language.

# Android Run-times

It is part of a library consisting of two parts managed by the “Android OS” as follows:

    Core Java Libraries are command compilation libraries. written in the language “Java”
    Dalvik Virtual Machine is a library used to process ".dex" files. This file is a program that we wrote to install on "Android". "compile" is from ".class". The ".dex" file is small.


# Linux Kernel Layer

This layer will work with all the “Layers” above. To manage various “hardware” or “device drivers” including memory, processor and “power”, “Android” uses “version” 2.6 of the Linux operating system.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.


_yay_

[back](./)
