# Getevent pretty print version with hex + dec and real screen coordinates 

Tested against some Android emulators and Kali Linux (on Virtual Box)

### Based on:

https://android.googlesource.com/platform/system/core.git/+/android-4.2.2_r1/toolbox/getevent.c

## Compile it 
```sh
g++ -std=c++2a -O3 -g0 ./geteventall.cpp
```

## run it 
```sh 
./a.out 1920 1080  # exe screen_width screen_height
```


### Standard version 

![](https://github.com/hansalemaos/getevent_pretty_print_linux/blob/main/output_getevent_normal.png?raw=true)


### Pretty print version 

![](https://github.com/hansalemaos/getevent_pretty_print_linux/blob/main/output_getevent_pretty.png?raw=true)





