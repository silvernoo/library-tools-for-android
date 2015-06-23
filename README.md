# library-tools-for-android
build opensource library &amp; tools for android platform

####all library and tools was compiled with android-19 API and 4.9 toolchains
1.  curl-4.7.2 (--host=arm-linux-androideabi --disable-debug --enable-static --disable-ftp --disable-ldap --disable-file --disable-rtsp --disable-proxy --disable-dict --disable-telnet --disable-tftp --disable-pop3 --disable-imap --disable-smb --disable-smtp --disable-gopher --disable-manual --disable-ipv6 --disable-sspi --disable-ntlm-wb --enable-shared=no --enable-static)
2.  libevent-2.0.22 (--host=arm-linux-androideabi --enable-static --disable-debug-mode)
3.  libgcrypt-1.6.3 (--host=arm-linux-androideabi --enable-static --with-libgpg-error-prefix)
4.  libgpg-error-1.19 (--host=arm-linux-androideabi --enable-static --disable-doc)
5.  libpcap (git clone @ 20150617) (--host=arm-linux-androideabi --with-pcap=linux)
6.  tcpdump (git clone @ 20150617) (--host=arm-linux-androideabi --with-crypto --with-cap-ng)
7.  openssl-1.0.1o (no-shared no-ssl2 no-ssl3 no-comp no-hw no-engine)
8.  wget-1.16.3 (--host=arm-linux-androideabi --enable-static --disable-nls --disable-debug --with-ssl=openssl)
9.  sqlite-3081002 (--host=arm-linux-androideabi --enable-static)
10. json-c (git clone @ 20150617) (--host=arm-linux-androideabi --enable-static)
11. libuv-1.6.1 (--host=arm-linux-androideabi --enable-static)
12. libpng (1.2 & 1.6) (v1.2: --without-libpng-compat --enable-static --host=arm-linux-androideabi CFLAGS=-O2 v1.6: --enable-static --host=arm-linux-androideabi CFLAGS=-O2)
13. libogg-1.3.2 (--host=arm-linux-androideabi --enable-static CFLAGS=-O2)
14. libvorbis-1.3.5 (--host=arm-linux-androideabi --enable-static --disable-oggtest --with-ogg-libraries)
15. libflac-1.3.1 (--host=arm-linux-androideabi --enable-static CFLAGS=-O2 --disable-thorough-tests --disable-doxygen-docs --disable-cpplibs --disable-xmms-plugin --disable-oggtest --with-ogg --disable-sse)
16. pcre-8.37 (--enable-static --host=arm-linux-androideabi CFLAGS=-O2 --enable-pcre16 --enable-pcre32 --enable-jit --enable-utf8 --disable-cpp)
17. qrencode-3.4.4 (--enable-static --host=arm-linux-androideabi CFLAGS=-O2)
18. bzip2-1.0.6 
19. libmaxminddb-1.0.4 (--enable-static --host=arm-linux-androideabi CFLAGS=-O2)
20. libjpeg-turbo-1.4.1 (--enable-static --host=arm-linux-androideabi CFLAGS=-O2 --with-jpeg7 --with-jpeg8 --without-java)
21. openssh-6.8p1 (--host=arm-linux-androideabi --enable-static CFLAGS=-O2 --disable-utmp --disable-utmpx --disable-wtmp --disable-wtmpx)
22. libiconv-1.14 (--enable-static --host=arm-linux-androideabi CFLAGS=-O2)
23. opus-1.1.1beta (--enable-static --host=arm-linux-androideabi CFLAGS=-O2)
