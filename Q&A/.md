# Some common issue I have met before
## Q1: Out of memory: Java heap memory on Android Studio.
## A1
The out of memory error looks like this:

    Out of memory: Java heap memory on Android Studio.

indicates that Java heap memory is exhausted when building (or rebuilding) project on Android Studio.

One way to solve this issue:

Increase the size of Java heap memory.

Additionally, I highly recommend that find out the reason why it uses so many Java heap memory when building (or rebuilding) project.

### Increase the Java heap memory.
#### Way 1: On Android Studio
1. On Android studio, find the gradle.properties.
2. Add this statement in gradle.properties. It will increase java heap memory to 4GB.

        # That's needed for java to be able the create the APK with our 300MB native  library
        # Basically we grant java a 4GB heap.
        org.gradle.jvmargs=-Xmx4608m

3. Rebuild the project.

![image](https://github.com/40843245/Java/assets/75050655/03765098-1469-4b8b-9146-ae795dd9e1c2)

#### Ref
https://stackoverflow.com/questions/27438145/out-of-memory-error-java-heap-memory-on-android-studio
