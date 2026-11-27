php
===

Build
-----
adev env:

    # cat /usr/local/etc/adev.d/a-php
    : ${V:=x.y}

    [[ "$V" == "8.6" ]] && V=8.6.z
    [[ "$V" == "8.5" ]] && V=8.5.z
    [[ "$V" == "8.4" ]] && V=8.4.z
    [[ "$V" == "8.3" ]] && V=8.3.z
    [[ "$V" == "8.2" ]] && V=8.2.z

    PROC=(php)
    INFO="PHP (8.6 8.5 8.4 8.3 8.2)"

    VER_EXT_APCU=x.y.z
