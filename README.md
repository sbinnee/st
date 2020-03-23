# Suckless Terminal (st)
Custom build of st by me.  
* Source : (https://st.suckless.org/)  
* Version : st 0.8.2 (2019-02-09)

## Unicode support
By default, st supports utf-8 very well, but there was a problem displaying 
color emoji. There found a bug in `libxft`, which is available in AUR (Not in 
main repo yet (2020-03-23)) [Link](https://gitlab.freedesktop.org/xorg/lib/libxft/-/merge_requests/1).  
Also configure `.config/fontconfig/fonts.conf`, then st should work properly for 
utf-8 unicode. But note that it does not support sequential unicode, namely 
utf-16 or higher (e.g. national flag emoji or skin color emoji).
