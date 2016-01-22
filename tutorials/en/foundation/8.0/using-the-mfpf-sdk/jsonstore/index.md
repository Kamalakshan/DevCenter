---
layout: tutorial
title: JSONStore
relevantTo: [cordova, ios, android]
weight: 8
show_children: true
---
## Overview
IBM MobileFirst™ Platform Foundation's **JSONStore** is an optional client-side API providing a lightweight, document-oriented storage system. JSONStore enables persistent storage of **JSON documents**. Documents in an application are available in JSONStore even when the device that is running the application is offline. This persistent, always-available storage can be useful to give users access to documents when, for example, there is no network connection available in the device.

#### Key features:

* Data indexing for efficient searching
* Data encryption in production environments
* Mechanism for tracking local-only changes to the stored data
* Support for multiple users

#### JSONStore is available in the following environments:

* Native: Android and iOS
* Cordova: Android, iOS, Windows 8.1 Universal and Windows 10 UWP
* Mobile Browser Simulator (not for production use)

> **Note:** This tutorial shows how to get started with the JSONStore API. Some features such as data encryption are beyond the scope of this tutorial. All features are documented in detail in the IBM MobileFirst Platform Foundation user documentation.

## Select an environment: