# Vindicator: *Advanced Undetectable Loader With a Pro Version*

## Vindicator uses "fibers" to run functions it have, the advantage of fibers over threads is that, "fibers" arent seen from the kernel:
`Based on: Windows Internals Seventh Edition Part 1   page: 19   chapter1: Concepts and tools`

![image](https://user-images.githubusercontent.com/91303729/138082158-fe172672-db70-4acb-bb9c-da68e59df382.png)

## The sample here is a poc of using fibers in windows for malicous act, so i created a pro version, ill talk about later

# USAGE:
* create your shellcode using cobalt-strike [preferably] or any other payload
* place your shellcode inside [encoder.py](https://github.com/JUICY00000/Vindicator/blob/main/Vindicator/test/encoder.py) and run it using `python2`
* after [encoder.py](https://github.com/JUICY00000/Vindicator/blob/main/Vindicator/test/encoder.py) output your encrypted shellcode copy and paste it inside [Source.cpp](https://github.com/JUICY00000/Vindicator/blob/f5a9121e2c6a55f25c12306c063d8d252c9972bf/Vindicator/test/test/Source.cpp#L88)
* build the code using visual studio 2017 or above as -- Release x64 -- 
* enjoy

# Features:
* Using fibers
* encoded shellcode
* decryption & injection of the shellode happens in the memory [byte by byte] and thus, less chance to get detected
* Using syscalls    


# The Vindicator Pro Version Features:
* using fibers [10 switches]
* ability to `detect sandboxes` 
* using syscalls
* Delete itself `while` execution [this is New af] so its impossible to get samples for analysis 
* the payload is a `pdf file format` that will be downloaded after the sandbox check
* injects to other processe(s) with `different way in injection and enumerating`
* u will get the source code of it with a cobalt strike profile, python script for the payload, and cobalt strike v4.3
* *The final price is 150$*

## i will upload a demo vd about the pro version later on ...
