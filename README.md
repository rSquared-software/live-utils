# LiveUtils
Library with helpful LiveData.
Based on Androidx artifacts.
Writen in Kotlin.

## Gradle Dependency (jitpack.io)

project level _build.gradle_
```Gradle
allprojects {
    repositories {
        ...
	maven { url 'https://jitpack.io' }
    }
}
```

app _build.gradle_
```Gradle
dependencies {
    implementation 'software.rsquared:live-utils:1.0.2'
}
```
[![](https://jitpack.io/v/software.rsquared/live-utils.svg)](https://jitpack.io/#software.rsquared/live-utils)

## What's inside?

* LiveEvent - This is just renamed _SingleLiveEvent_ class from one of google samples. 
* PresetLiveData - Simple LiveData that only have one value passed on it's creation.
* ObserverAwareLiveData - Exposes _hasObservers_ LiveData that get updates when this LiveData is observed.
* ObserverAwareMediatorLiveData - Same as above but extends MediatorLiveData. 
* _todo more..._
