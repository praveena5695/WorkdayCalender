# workday

This take-home assignment evaluates your knowledge and/or resourcefulness
with a simple programming exercise in Java, using JUnit as the test framework,
Gradle as the build system, and Git as the version control system.

## Requirements

You will need to download the following software on your computer:

1. OpenJDK 17 or later. You can download it for free from https://adoptium.net/temurin/archive/?version=17
2. Gradle 8.1.1 or later.  You can download it for free from https://gradle.org/releases/

Set the `JAVA_HOME` environment variable to point to the directory where the JDK was installed
and then add Gradle's `bin` directory to your `PATH` environment variable.

## The exercise

We want to know what date it will be `n` work days (often called "business days") from a given start date.

For example, suppose today is October 5th 2023, and we want to know what day it will be in `n = 2` work days.

The answer would be October 9th.

```text
    October 2023    
Su Mo Tu We Th Fr Sa
 1  2  3  4  5  6  7
 8  9 10 11 12 13 14
15 16 17 18 19 20 21
22 23 24 25 26 27 28
29 30 31
```


## Directions

Throughout these steps, make small, focused commits along the way to show your work.

1. Create a feature branch whose name includes your name.
2. Upgrade JUnit to version 5.
3. Remove the unused `guava` dependency.
4. Implement the `App#getWorkday(Date, int)` method, with unit tests.  Bonus points for TDD.
5. Remove untracked & ignored files, then create a ZIP archive of the directory and e-mail it back to your contact.
