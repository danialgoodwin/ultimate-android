# ultimate-android
Library of common Android functionality and related notes



## Experimental

- Idea: Encapsulate all Android calls to suspend methods that will be on Dispatchers.Main as needed. Always toast startup time. Launch many Coroutines. 

'Enterprise Android'
- Everything would probably be encapsulated
- Priorities:
    - Ability to use with other platforms (hmm, base interfaces wouldn't really be in an '*Android' repo. I need to learn more about KMP and Compose) 
    - No crashes
    - Performance (start up and use)
    - Memory

