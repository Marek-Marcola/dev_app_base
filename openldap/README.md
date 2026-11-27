openldap
========

Build
-----
adev env:

    # cat /usr/local/etc/adev.d/a-openldap
    : ${V:=x.y}

    [[ "$V" == "2.7" ]] && V=2.7.z
    [[ "$V" == "2.6" ]] && V=2.6.z
    [[ "$V" == "2.5" ]] && V=2.5.z
    [[ "$V" == "2.4" ]] && V=2.4.z

    PROCS=(openldap)
    INFO="OpenLDAP (2.7 2.6 2.5 2.4)"
