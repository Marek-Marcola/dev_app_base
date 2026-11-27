nginx
=====

Build
-----
adev env:

    # cat /usr/local/etc/adev.d/a-nginx
    : ${V:=x.y.z}

    PROCS=(nginx)

    VER_MODSECURITY=x.y.z
    VER_MODSECURITY_NGINX=x.y.z
    VER_MODULE_DAV_EXT=x.y.z
    VER_MODULE_FANCYINDEX=x.y.z
    VER_MODULE_HEADERS_MORE=x.y.z
