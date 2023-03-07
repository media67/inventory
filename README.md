Inventory - Starter Code
==================================

Starter code for Android Basics in Kotlin.

Introduction
------------

This app is an stater code for an Inventory tracking app. Demos how to add, update, sell, and delete
 items from the local database.
This app demonstrated
the use of Android Jetpack component [Room](https://developer.android.com/training/data-storage/room) database.  

The app also leverages [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel),
[LiveData](https://developer.android.com/topic/libraries/architecture/livedata),
[Flow](https://developer.android.com/kotlin/flow),
[View Binding](https://developer.android.com/topic/libraries/view-binding),
and [Navigation](https://developer.android.com/topic/libraries/architecture/navigation/)
with the SafeArgs plugin for parameter passing between fragments.

Pre-requisites
--------------

You need to know:
- How to create and use fragments.
- How to navigate between fragments, and use safeArgs to pass data between fragments.
- How to use architecture components including ViewModel, LiveData, and LiveData transformations.
- How to use coroutines for long-running tasks.
- RecyclerView and adapters
- SQLite database and the SQLite query language


Getting Started
---------------

1. Download and run the app.

Links found during the codelab
------------------------------

[Room](https://developer.android.com/topic/libraries/architecture/room)
[Data entities](https://developer.android.com/training/data-storage/room/defining-data)
[Data access objects (DAOs)](https://developer.android.com/training/data-storage/room/accessing-data)
[Database class](https://developer.android.com/reference/kotlin/androidx/room/Database)
[Entity](https://developer.android.com/reference/androidx/room/Entity)
[Primary key](https://developer.android.com/reference/androidx/room/PrimaryKey)
[Single responsibility principle](https://en.wikipedia.org/wiki/Single-responsibility_principle)
[onConflictStrategy](https://developer.android.com/reference/androidx/room/OnConflictStrategy.html)
[RoomDatabase](https://developer.android.com/reference/androidx/room/RoomDatabase)
[Database Inspector](https://developer.android.com/studio/inspect/database)

Learn more
----------
Android Developer Documentation
- [Save data in a local database using Room](https://developer.android.com/training/data-storage/room)
- [androidx.room](https://developer.android.com/reference/androidx/room/package-summary)
- [7 Pro-tips for Room](https://medium.com/androiddevelopers/7-pro-tips-for-room-fbadea4bfbd1)

Blog Posts
- [The one and only object. Kotlin Vocabulary](https://medium.com/androiddevelopers/the-one-and-only-object-5dfd2cf7ab9b)
- [Singleton pattern](https://en.wikipedia.org/wiki/Singleton_pattern)

Videos
- [Kotlin: Using Room Kotlin APIs](https://www.youtube.com/watch?v=vsDkhRTMdA0)
- [Database inspector](https://www.youtube.com/watch?v=UMc7Tu0nKYQ)

Other Documentation And Articles
- [Singleton pattern](https://en.wikipedia.org/wiki/Singleton_pattern)
- [Companion objects](https://kotlinlang.org/docs/reference/object-declarations.html)
- [SQLite Tutorial - An Easy Way To Master SQLite Faster](https://www.sqlitetutorial.net/)