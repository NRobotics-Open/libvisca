 /usr/bin/mkdir -p '/usr/local/lib'
 /bin/bash ../libtool   --mode=install /usr/bin/install -c   libvisca.la '/usr/local/lib'
libtool: install: /usr/bin/install -c .libs/libvisca.so.3.0.1 /usr/local/lib/libvisca.so.3.0.1
libtool: install: (cd /usr/local/lib && { ln -s -f libvisca.so.3.0.1 libvisca.so.3 || { rm -f libvisca.so.3 && ln -s libvisca.so.3.0.1 libvisca.so.3; }; })
libtool: install: (cd /usr/local/lib && { ln -s -f libvisca.so.3.0.1 libvisca.so || { rm -f libvisca.so && ln -s libvisca.so.3.0.1 libvisca.so; }; })
libtool: install: /usr/bin/install -c .libs/libvisca.lai /usr/local/lib/libvisca.la
libtool: install: /usr/bin/install -c .libs/libvisca.a /usr/local/lib/libvisca.a
libtool: install: chmod 644 /usr/local/lib/libvisca.a
libtool: install: ranlib /usr/local/lib/libvisca.a
libtool: finish: PATH="/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin:/sbin" ldconfig -n /usr/local/lib
----------------------------------------------------------------------
Libraries have been installed in:
   /usr/local/lib

If you ever happen to want to link against installed libraries
in a given directory, LIBDIR, you must either use libtool, and
specify the full pathname of the library, or use the '-LLIBDIR'
flag during linking and do at least one of the following:
   - add LIBDIR to the 'LD_LIBRARY_PATH' environment variable
     during execution
   - add LIBDIR to the 'LD_RUN_PATH' environment variable
     during linking
   - use the '-Wl,-rpath -Wl,LIBDIR' linker flag
   - have your system administrator add LIBDIR to '/etc/ld.so.conf'
