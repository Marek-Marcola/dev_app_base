haproxy
=======

Build
-----
adev env:

    # cat /usr/local/etc/adev.d/a-haproxy
    : ${V:=x.y}

    [[ "$V" == "3.4" ]] && V=3.4.z

    PROCS=(haproxy)
    INFO="HAProxy (3.4)"
