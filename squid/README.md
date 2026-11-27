squid
=====

Build
-----
adev env:

    # cat /usr/local/etc/adev.d/a-squid
    : ${V:=x}

    [[ "$V" == "7" ]] && V=7.y
    [[ "$V" == "6" ]] && V=6.y
    [[ "$V" == "5" ]] && V=5.y

    PROC=(squid)
    INFO="Squid (7 6 5)"

    VER_LANG=yyyymmdd
