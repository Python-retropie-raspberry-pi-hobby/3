Log started at: Thu Dec 31 09:48:31 EST 2020

RetroPie-Setup version: 4.7.2 (ac8d8775)
System: rpi4 (aarch64) - Raspbian GNU/Linux 10 (buster) - Linux retropie 5.4.79-v8+ #1373 SMP PREEMPT Mon Nov 23 13:32:41 GMT 2020 aarch64 GNU/Linux

= = = = = = = = = = = = = = = = = = = = =
Installing dependencies for 'lr-melonDS' : NDS/DSI emu requries bios and firmware from DS/DSI port for libretro
= = = = = = = = = = = = = = = = = = = = =

Did not find needed dependencies: libcurl4-gnutls-dev. Trying to install them now.
Hit:1 http://raspbian.raspberrypi.org/raspbian buster InRelease
Hit:2 http://archive.raspberrypi.org/debian buster InRelease
Reading package lists...
Reading package lists...
Building dependency tree...
Reading state information...
Suggested packages:
  libcurl4-doc libgnutls28-dev libidn11-dev libkrb5-dev libldap2-dev
  librtmp-dev libssh2-1-dev
The following packages will be REMOVED:
  libcurl4-openssl-dev
The following NEW packages will be installed:
  libcurl4-gnutls-dev
0 upgraded, 1 newly installed, 1 to remove and 0 not upgraded.
Need to get 0 B/365 kB of archives.
After this operation, 3072 B disk space will be freed.
(Reading database ... 
(Reading database ... 5%
(Reading database ... 10%
(Reading database ... 15%
(Reading database ... 20%
(Reading database ... 25%
(Reading database ... 30%
(Reading database ... 35%
(Reading database ... 40%
(Reading database ... 45%
(Reading database ... 50%
(Reading database ... 55%
(Reading database ... 60%
(Reading database ... 65%
(Reading database ... 70%
(Reading database ... 75%
(Reading database ... 80%
(Reading database ... 85%
(Reading database ... 90%
(Reading database ... 95%
(Reading database ... 100%
(Reading database ... 132624 files and directories currently installed.)
Removing libcurl4-openssl-dev:armhf (7.64.0-4+deb10u1) ...
Selecting previously unselected package libcurl4-gnutls-dev:armhf.
(Reading database ... 
(Reading database ... 5%
(Reading database ... 10%
(Reading database ... 15%
(Reading database ... 20%
(Reading database ... 25%
(Reading database ... 30%
(Reading database ... 35%
(Reading database ... 40%
(Reading database ... 45%
(Reading database ... 50%
(Reading database ... 55%
(Reading database ... 60%
(Reading database ... 65%
(Reading database ... 70%
(Reading database ... 75%
(Reading database ... 80%
(Reading database ... 85%
(Reading database ... 90%
(Reading database ... 95%
(Reading database ... 100%
(Reading database ... 132602 files and directories currently installed.)
Preparing to unpack .../libcurl4-gnutls-dev_7.64.0-4+deb10u1_armhf.deb ...
Unpacking libcurl4-gnutls-dev:armhf (7.64.0-4+deb10u1) ...
Setting up libcurl4-gnutls-dev:armhf (7.64.0-4+deb10u1) ...
Processing triggers for man-db (2.8.5-2) ...
/home/pi/RetroPie-Setup/tmp/build/lr-melonDS /home/pi

= = = = = = = = = = = = = = = = = = = = =
Getting sources for 'lr-melonDS' : NDS/DSI emu requries bios and firmware from DS/DSI port for libretro
= = = = = = = = = = = = = = = = = = = = =

git clone --recursive --depth 1 --branch master "https://github.com/libretro/melonDS.git" "/home/pi/RetroPie-Setup/tmp/build/lr-melonDS"
Cloning into '/home/pi/RetroPie-Setup/tmp/build/lr-melonDS'...
HEAD is now in branch 'master' at commit '7bbf8e1606697f7591072d05b61fae84e8b49455'
/home/pi
/home/pi/RetroPie-Setup/tmp/build/lr-melonDS /home/pi

= = = = = = = = = = = = = = = = = = = = =
Building 'lr-melonDS' : NDS/DSI emu requries bios and firmware from DS/DSI port for libretro
= = = = = = = = = = = = = = = = = = = = =

/home/pi/RetroPie-Setup/scriptmodules/libretrocores/lr-melonDS.sh: line 35: cd: melon-ds/src/frontend/libretro: No such file or directory
rm -f ./src/xxhash/xxhash.o ./src/tiny-AES-c/aes.o ./src/libretro/libretro-common/compat/compat_strl.o ./src/libretro/libretro-common/compat/fopen_utf8.o ./src/libretro/libretro-common/compat/compat_posix_string.o ./src/libretro/libretro-common/compat/compat_strcasestr.o ./src/libretro/libretro-common/encodings/encoding_utf.o ./src/libretro/libretro-common/file/file_path.o ./src/libretro/libretro-common/streams/file_stream.o ./src/libretro/libretro-common/streams/file_stream_transforms.o ./src/libretro/libretro-common/streams/memory_stream.o ./src/libretro/libretro-common/string/stdstring.o ./src/libretro/libretro-common/vfs/vfs_implementation.o ./src/libretro/libretro-common/glsm/glsm.o ./src/libretro/libretro-common/glsym/rglgen.o ./src/libretro/libretro-common/glsym/glsym_gl.o ./src/libretro/libretro-common/rthreads/rthreads.o ./src/libretro/libretro-common/rthreads/rsemaphore.o ./src/NDS.o ./src/AREngine.o ./src/ARM.o ./src/ARMInterpreter.o ./src/ARMInterpreter_ALU.o ./src/ARMInterpreter_Branch.o ./src/ARMInterpreter_LoadStore.o ./src/CP15.o ./src/CRC32.o ./src/DMA.o ./src/DSi.o ./src/DSi_AES.o ./src/DSi_Camera.o ./src/DSi_I2C.o ./src/DSi_NDMA.o ./src/DSi_NWifi.o ./src/DSi_SD.o ./src/DSi_SPI_TSC.o ./src/DSiCrypto.o ./src/GBACart.o ./src/GPU.o ./src/GPU2D.o ./src/GPU2DSoft.o ./src/GPU3D.o ./src/GPU3D_Soft.o ./src/NDSCart.o ./src/RTC.o ./src/Savestate.o ./src/SPI.o ./src/SPU.o ./src/Wifi.o ./src/WifiAP.o ./src/libretro/config.o ./src/libretro/input.o ./src/libretro/libretro.o ./src/libretro/platform.o ./src/libretro/screenlayout.o ./src/libretro/utils.o ./src/GPU_OpenGL.o ./src/GPU3D_OpenGL.o ./src/OpenGLSupport.o ./src/libretro/opengl.o  melonds_libretro.so
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/xxhash/xxhash.o src/xxhash/xxhash.c
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/tiny-AES-c/aes.o src/tiny-AES-c/aes.c
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/libretro-common/compat/compat_strl.o src/libretro/libretro-common/compat/compat_strl.c
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/libretro-common/compat/fopen_utf8.o src/libretro/libretro-common/compat/fopen_utf8.c
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/libretro-common/compat/compat_posix_string.o src/libretro/libretro-common/compat/compat_posix_string.c
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/libretro-common/compat/compat_strcasestr.o src/libretro/libretro-common/compat/compat_strcasestr.c
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/libretro-common/encodings/encoding_utf.o src/libretro/libretro-common/encodings/encoding_utf.c
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/libretro-common/file/file_path.o src/libretro/libretro-common/file/file_path.c
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/libretro-common/streams/file_stream.o src/libretro/libretro-common/streams/file_stream.c
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/libretro-common/streams/file_stream_transforms.o src/libretro/libretro-common/streams/file_stream_transforms.c
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/libretro-common/streams/memory_stream.o src/libretro/libretro-common/streams/memory_stream.c
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/libretro-common/string/stdstring.o src/libretro/libretro-common/string/stdstring.c
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/libretro-common/vfs/vfs_implementation.o src/libretro/libretro-common/vfs/vfs_implementation.c
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/libretro-common/glsm/glsm.o src/libretro/libretro-common/glsm/glsm.c
src/libretro/libretro-common/vfs/vfs_implementation.c: In function 'retro_vfs_file_open_impl':
src/libretro/libretro-common/vfs/vfs_implementation.c:287:36: warning: unused variable 'path_len' [-Wunused-variable]
    int                             path_len = (int)strlen(path);
                                    ^~~~~~~~
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/libretro-common/glsym/rglgen.o src/libretro/libretro-common/glsym/rglgen.c
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/libretro-common/glsym/glsym_gl.o src/libretro/libretro-common/glsym/glsym_gl.c
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/libretro-common/rthreads/rthreads.o src/libretro/libretro-common/rthreads/rthreads.c
cc  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/libretro-common/rthreads/rsemaphore.o src/libretro/libretro-common/rthreads/rsemaphore.c
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/NDS.o src/NDS.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/AREngine.o src/AREngine.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/ARM.o src/ARM.cpp
src/ARM.cpp: In member function 'virtual void ARMv4::JumpTo(u32, bool)':
src/ARM.cpp:325:9: warning: unused variable 'oldregion' [-Wunused-variable]
     u32 oldregion = R[15] >> 23;
         ^~~~~~~~~
src/ARM.cpp:326:9: warning: unused variable 'newregion' [-Wunused-variable]
     u32 newregion = addr >> 23;
         ^~~~~~~~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/ARMInterpreter.o src/ARMInterpreter.cpp
src/NDS.cpp: In function 'bool NDS::DoSavestate_Scheduler(Savestate*)':
src/NDS.cpp:659:28: warning: comparison of integer expressions of different signedness: 'u32' {aka 'unsigned int'} and 'int' [-Wsign-compare]
                 if (funcid == -1)
                     ~~~~~~~^~~~~
src/NDS.cpp:680:24: warning: comparison of integer expressions of different signedness: 'u32' {aka 'unsigned int'} and 'int' [-Wsign-compare]
             if (funcid != -1)
                 ~~~~~~~^~~~~
src/NDS.cpp:689:27: warning: comparison of integer expressions of different signedness: 'int' and 'u32' {aka 'unsigned int'} [-Wsign-compare]
                     if (j == funcid) break;
                         ~~^~~~~~~~~
src/NDS.cpp: In function 'void NDS::NocashPrint(u32, u32)':
src/NDS.cpp:1432:67: warning: format '%lu' expects argument of type 'long unsigned int', but argument 3 has type 'u64' {aka 'long long unsigned int'} [-Wformat=]
                 else if (!strcmp(cmd, "totalclks")) sprintf(subs, "%lu", GetSysClockCycles(0));
                                                                   ^~~~~  ~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1433:66: warning: format '%lu' expects argument of type 'long unsigned int', but argument 3 has type 'u64' {aka 'long long unsigned int'} [-Wformat=]
                 else if (!strcmp(cmd, "lastclks")) sprintf(subs, "%lu", GetSysClockCycles(1));
                                                                  ^~~~~  ~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1436:35: warning: zero-length gnu_printf format string [-Wformat-zero-length]
                     sprintf(subs, "");
                                   ^~
src/NDS.cpp: In function 'void NDS::RunTimer(u32, s32)':
src/NDS.cpp:1513:9: warning: unused variable 'oldcount' [-Wunused-variable]
     u32 oldcount = timer->Counter;
         ^~~~~~~~
src/NDS.cpp: In function 'void NDS::DivDone(u32)':
src/NDS.cpp:1693:18: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
                 *(s64*)&DivRemainder[0] = num;
                  ^~~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1695:26: warning: comparison of integer expressions of different signedness: 's32' {aka 'int'} and 'unsigned int' [-Wsign-compare]
             else if (num == -0x80000000 && den == -1)
                      ~~~~^~~~~~~~~~~~~~
src/NDS.cpp:1697:18: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
                 *(s64*)&DivQuotient[0] = 0x80000000;
                  ^~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1701:18: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
                 *(s64*)&DivQuotient[0] = (s64)(num / den);
                  ^~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1702:18: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
                 *(s64*)&DivRemainder[0] = (s64)(num % den);
                  ^~~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1710:24: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
             s64 num = *(s64*)&DivNumerator[0];
                        ^~~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1714:18: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
                 *(s64*)&DivQuotient[0] = (num<0) ? 1:-1;
                  ^~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1715:18: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
                 *(s64*)&DivRemainder[0] = num;
                  ^~~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1717:26: warning: comparison of integer expressions of different signedness: 's64' {aka 'long long int'} and 'long long unsigned int' [-Wsign-compare]
             else if (num == -0x8000000000000000 && den == -1)
                      ~~~~^~~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1719:18: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
                 *(s64*)&DivQuotient[0] = 0x8000000000000000;
                  ^~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1723:18: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
                 *(s64*)&DivQuotient[0] = (s64)(num / den);
                  ^~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1724:18: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
                 *(s64*)&DivRemainder[0] = (s64)(num % den);
                  ^~~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1731:24: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
             s64 num = *(s64*)&DivNumerator[0];
                        ^~~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1732:24: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
             s64 den = *(s64*)&DivDenominator[0];
                        ^~~~~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1735:18: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
                 *(s64*)&DivQuotient[0] = (num<0) ? 1:-1;
                  ^~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1736:18: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
                 *(s64*)&DivRemainder[0] = num;
                  ^~~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1738:26: warning: comparison of integer expressions of different signedness: 's64' {aka 'long long int'} and 'long long unsigned int' [-Wsign-compare]
             else if (num == -0x8000000000000000 && den == -1)
                      ~~~~^~~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1740:18: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
                 *(s64*)&DivQuotient[0] = 0x8000000000000000;
                  ^~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1744:18: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
                 *(s64*)&DivQuotient[0] = (s64)(num / den);
                  ^~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp:1745:18: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
                 *(s64*)&DivRemainder[0] = (s64)(num % den);
                  ^~~~~~~~~~~~~~~~~~~~~~
src/NDS.cpp: In function 'void NDS::SqrtDone(u32)':
src/NDS.cpp:1775:16: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
         val = *(u64*)&SqrtVal[0];
                ^~~~~~~~~~~~~~~~~
src/NDS.cpp: In function 'u16 NDS::ARM9IORead16(u32)':
src/NDS.cpp:2886:30: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
     case 0x040000E0: return ((u16*)DMA9Fill)[0];
                             ~^~~~~~~~~~~~~~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/ARMInterpreter_ALU.o src/ARMInterpreter_ALU.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/ARMInterpreter_Branch.o src/ARMInterpreter_Branch.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/ARMInterpreter_LoadStore.o src/ARMInterpreter_LoadStore.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/CP15.o src/CP15.cpp
src/NDS.cpp: In function 'u64 NDS::GetSysClockCycles(int)':
src/NDS.cpp:1370:12: warning: 'ret' may be used uninitialized in this function [-Wmaybe-uninitialized]
     return ret;
            ^~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/CRC32.o src/CRC32.cpp
src/ARMInterpreter_LoadStore.cpp: In function 'void ARMInterpreter::A_LDM(ARM*)':
src/ARMInterpreter_LoadStore.cpp:456:36: warning: 'wbbase' may be used uninitialized in this function [-Wmaybe-uninitialized]
                     cpu->R[baseid] = wbbase;
                     ~~~~~~~~~~~~~~~^~~~~~~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/DMA.o src/DMA.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/DSi.o src/DSi.cpp
src/DMA.cpp: In instantiation of 'void DMA::Run9() [with int ConsoleType = 0]':
src/DMA.cpp:425:44:   required from 'void DMA::Run() [with int ConsoleType = 0]'
src/DMA.cpp:429:27:   required from here
src/DMA.cpp:194:10: warning: unused variable 'burststart' [-Wunused-variable]
     bool burststart = (Running == 2);
          ^~~~~~~~~~
src/DMA.cpp: In instantiation of 'void DMA::Run7() [with int ConsoleType = 0]':
src/DMA.cpp:426:44:   required from 'void DMA::Run() [with int ConsoleType = 0]'
src/DMA.cpp:429:27:   required from here
src/DMA.cpp:313:10: warning: unused variable 'burststart' [-Wunused-variable]
     bool burststart = (Running == 2);
          ^~~~~~~~~~
src/DMA.cpp: In instantiation of 'void DMA::Run9() [with int ConsoleType = 1]':
src/DMA.cpp:425:44:   required from 'void DMA::Run() [with int ConsoleType = 1]'
src/DMA.cpp:430:27:   required from here
src/DMA.cpp:194:10: warning: unused variable 'burststart' [-Wunused-variable]
     bool burststart = (Running == 2);
          ^~~~~~~~~~
src/DMA.cpp: In instantiation of 'void DMA::Run7() [with int ConsoleType = 1]':
src/DMA.cpp:426:44:   required from 'void DMA::Run() [with int ConsoleType = 1]'
src/DMA.cpp:430:27:   required from here
src/DMA.cpp:313:10: warning: unused variable 'burststart' [-Wunused-variable]
     bool burststart = (Running == 2);
          ^~~~~~~~~~
src/DSi.cpp: In function 'void DSi::ARM9IOWrite32(u32, u32)':
src/DSi.cpp:1615:17: warning: unused variable 'oldram' [-Wunused-variable]
             u32 oldram = (SCFG_EXT[0] >> 14) & 0x3;
                 ^~~~~~
src/DSi.cpp:1616:17: warning: unused variable 'newram' [-Wunused-variable]
             u32 newram = (val >> 14) & 0x3;
                 ^~~~~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/DSi_AES.o src/DSi_AES.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/DSi_Camera.o src/DSi_Camera.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/DSi_I2C.o src/DSi_I2C.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/DSi_NDMA.o src/DSi_NDMA.cpp
src/DSi_I2C.cpp: In function 'void DSi_BPTWL::Write(u8, bool)':
src/DSi_I2C.cpp:100:16: warning: comparison of integer expressions of different signedness: 'u32' {aka 'unsigned int'} and 'int' [-Wsign-compare]
     if (CurPos == -1)
         ~~~~~~~^~~~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/DSi_NWifi.o src/DSi_NWifi.cpp
src/DSi_NWifi.cpp: In member function 'virtual void DSi_NWifi::Reset()':
src/DSi_NWifi.cpp:191:16: warning: format '%X' expects a matching 'unsigned int' argument [-Wformat=]
         printf("NWifi: unknown hardware type %02X, assuming AR6002\n");
                ^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
src/DSi_NWifi.cpp: In member function 'void DSi_NWifi::WriteBlock()':
src/DSi_NWifi.cpp:695:13: warning: suggest parentheses around assignment used as truth value [-Wparentheses]
     if (len = Host->DataTX(data, len))
         ~~~~^~~~~~~~~~~~~~~~~~~~~~~~~
src/DSi_NWifi.cpp: In member function 'void DSi_NWifi::BMI_Command()':
src/DSi_NWifi.cpp:751:31: warning: comparison of integer expressions of different signedness: 'int' and 'u32' {aka 'unsigned int'} [-Wsign-compare]
             for (int i = 0; i < len; i++)
                             ~~^~~~~
src/DSi_NWifi.cpp:753:20: warning: unused variable 'val' [-Wunused-variable]
                 u8 val = Mailbox[0]->Read();
                    ^~~
src/DSi_NWifi.cpp:805:31: warning: comparison of integer expressions of different signedness: 'int' and 'u32' {aka 'unsigned int'} [-Wsign-compare]
             for (int i = 0; i < len; i++)
                             ~~^~~~~
src/DSi_NWifi.cpp:807:20: warning: unused variable 'val' [-Wunused-variable]
                 u8 val = Mailbox[0]->Read();
                    ^~~
src/DSi_NWifi.cpp: In member function 'void DSi_NWifi::HTC_Command()':
src/DSi_NWifi.cpp:824:9: warning: unused variable 'h0' [-Wunused-variable]
     u16 h0 = MB_Read16(0);
         ^~
src/DSi_NWifi.cpp:826:9: warning: unused variable 'h2' [-Wunused-variable]
     u16 h2 = MB_Read16(0);
         ^~
src/DSi_NWifi.cpp: In member function 'void DSi_NWifi::WMI_ConnectToNetwork()':
src/DSi_NWifi.cpp:1149:8: warning: unused variable 'pCryptoLen' [-Wunused-variable]
     u8 pCryptoLen = Mailbox[0]->Read();
        ^~~~~~~~~~
src/DSi_NWifi.cpp:1151:8: warning: unused variable 'gCryptoLen' [-Wunused-variable]
     u8 gCryptoLen = Mailbox[0]->Read();
        ^~~~~~~~~~
src/DSi_NWifi.cpp:1160:9: warning: unused variable 'channel' [-Wunused-variable]
     u16 channel = MB_Read16(0);
         ^~~~~~~
src/DSi_NWifi.cpp:1166:9: warning: unused variable 'flags' [-Wunused-variable]
     u32 flags = MB_Read32(0);
         ^~~~~
src/DSi_NWifi.cpp: In member function 'void DSi_NWifi::SendWMIEvent(u8, u16, u8*, u32)':
src/DSi_NWifi.cpp:1310:23: warning: comparison of integer expressions of different signedness: 'int' and 'u32' {aka 'unsigned int'} [-Wsign-compare]
     for (int i = 0; i < len; i++)
                     ~~^~~~~
src/DSi_NWifi.cpp: In member function 'void DSi_NWifi::SendWMIBSSInfo(u8, u8*, u32)':
src/DSi_NWifi.cpp:1387:23: warning: comparison of integer expressions of different signedness: 'int' and 'u32' {aka 'unsigned int'} [-Wsign-compare]
     for (int i = 0; i < len; i++)
                     ~~^~~~~
src/DSi_NDMA.cpp: In member function 'void DSi_NDMA::Run9()':
src/DSi_NDMA.cpp:169:10: warning: unused variable 'burststart' [-Wunused-variable]
     bool burststart = (Running == 2);
          ^~~~~~~~~~
src/DSi_NDMA.cpp: In member function 'void DSi_NDMA::Run7()':
src/DSi_NDMA.cpp:258:10: warning: unused variable 'burststart' [-Wunused-variable]
     bool burststart = (Running == 2);
          ^~~~~~~~~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/DSi_SD.o src/DSi_SD.cpp
src/DSi_SD.cpp: In member function 'void DSi_SDHost::UpdateData32IRQ()':
src/DSi_SD.cpp:163:29: warning: comparison of integer expressions of different signedness: 'u32' {aka 'unsigned int'} and 'int' [-Wsign-compare]
     if (DataFIFO32->Level() >= (BlockLen32>>2)) Data32IRQ |= (1<<8);
         ~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/DSi_SPI_TSC.o src/DSi_SPI_TSC.cpp
src/DSi_SD.cpp: In member function 'void DSi_SDHost::SendResponse(u32, bool)':
src/DSi_SD.cpp:231:6: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
     *(u32*)&ResponseBuffer[6] = *(u32*)&ResponseBuffer[4];
      ^~~~~~~~~~~~~~~~~~~~~~~~
src/DSi_SD.cpp:231:34: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
     *(u32*)&ResponseBuffer[6] = *(u32*)&ResponseBuffer[4];
                                  ^~~~~~~~~~~~~~~~~~~~~~~~
src/DSi_SD.cpp:232:6: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
     *(u32*)&ResponseBuffer[4] = *(u32*)&ResponseBuffer[2];
      ^~~~~~~~~~~~~~~~~~~~~~~~
src/DSi_SD.cpp:232:34: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
     *(u32*)&ResponseBuffer[4] = *(u32*)&ResponseBuffer[2];
                                  ^~~~~~~~~~~~~~~~~~~~~~~~
src/DSi_SD.cpp:233:6: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
     *(u32*)&ResponseBuffer[2] = *(u32*)&ResponseBuffer[0];
      ^~~~~~~~~~~~~~~~~~~~~~~~
src/DSi_SD.cpp:233:34: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
     *(u32*)&ResponseBuffer[2] = *(u32*)&ResponseBuffer[0];
                                  ^~~~~~~~~~~~~~~~~~~~~~~~
src/DSi_SD.cpp:234:6: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
     *(u32*)&ResponseBuffer[0] = val;
      ^~~~~~~~~~~~~~~~~~~~~~~~
src/DSi_SD.cpp: In member function 'u16 DSi_SDHost::ReadFIFO16()':
src/DSi_SD.cpp:491:19: warning: unused variable 'dev' [-Wunused-variable]
     DSi_SDDevice* dev = Ports[PortSelect & 0x1];
                   ^~~
src/DSi_SD.cpp: In member function 'u32 DSi_SDHost::ReadFIFO32()':
src/DSi_SD.cpp:512:19: warning: unused variable 'dev' [-Wunused-variable]
     DSi_SDDevice* dev = Ports[PortSelect & 0x1];
                   ^~~
src/DSi_SD.cpp: In member function 'void DSi_SDHost::WriteFIFO16(u16)':
src/DSi_SD.cpp:644:19: warning: unused variable 'dev' [-Wunused-variable]
     DSi_SDDevice* dev = Ports[PortSelect & 0x1];
                   ^~~
src/DSi_SD.cpp: In member function 'u32 DSi_MMCStorage::WriteBlock(u64)':
src/DSi_SD.cpp:983:13: warning: suggest parentheses around assignment used as truth value [-Wparentheses]
     if (len = Host->DataTX(data, len))
         ~~~~^~~~~~~~~~~~~~~~~~~~~~~~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/DSiCrypto.o src/DSiCrypto.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/GBACart.o src/GBACart.cpp
src/GBACart.cpp: In function 'void GBACart_SRAM::Write8(u32, u8)':
src/GBACart.cpp:462:8: warning: unused variable 'prev' [-Wunused-variable]
     u8 prev = *(u8*)&SRAM[addr];
        ^~~~
src/GBACart.cpp: In function 'void GBACart_SRAM::Write16(u32, u16)':
src/GBACart.cpp:469:9: warning: unused variable 'prev' [-Wunused-variable]
     u16 prev = *(u16*)&SRAM[addr];
         ^~~~
src/GBACart.cpp: In function 'void GBACart_SRAM::Write32(u32, u32)':
src/GBACart.cpp:477:9: warning: unused variable 'prev' [-Wunused-variable]
     u32 prev = *(u32*)&SRAM[addr];
         ^~~~
src/GBACart.cpp: In function 'void GBACart::Eject()':
src/GBACart.cpp:549:15: warning: converting to non-pointer type 'u32' {aka 'unsigned int'} from NULL [-Wconversion-null]
     CartCRC = NULL;
               ^~~~
src/GBACart.cpp:550:14: warning: converting to non-pointer type 'u32' {aka 'unsigned int'} from NULL [-Wconversion-null]
     CartID = NULL;
              ^~~~
src/GBACart.cpp: In function 'bool GBACart::LoadROM(const char*, const char*)':
src/GBACart.cpp:648:23: warning: comparison of integer expressions of different signedness: 'int' and 'unsigned int' [-Wsign-compare]
     for (int i = 0; i < sizeof(SOLAR_SENSOR_GAMECODES)/sizeof(SOLAR_SENSOR_GAMECODES[0]); i++)
                     ~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/GPU.o src/GPU.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/GPU2D.o src/GPU2D.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/GPU2DSoft.o src/GPU2DSoft.cpp
src/GPU.cpp: In function 'void GPU::StartScanline(u32)':
src/GPU.cpp:1054:25: warning: comparison of integer expressions of different signedness: 'u32' {aka 'unsigned int'} and 'int' [-Wsign-compare]
     else if (NextVCount != -1)
              ~~~~~~~~~~~^~~~~
src/GPU2DSoft.cpp: In member function 'virtual void GPU2DSoft::DrawScanline(u32)':
src/GPU2DSoft.cpp:233:35: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
                 *(u64*)&dst[i] = *(u64*)&BGOBJLine[i];
                                   ^~~~~~~~~~~~~~~~~~~
src/GPU2DSoft.cpp: In member function 'void GPU2DSoft::DrawScanlineBGMode(u32)':
src/GPU2DSoft.cpp:660:12: warning: suggest explicit braces to avoid ambiguous 'else' [-Wdangling-else]
         if ((DispCnt & 0x1000) && NumSprites)
            ^
src/GPU2DSoft.cpp: In member function 'void GPU2DSoft::DrawScanlineBGMode6(u32)':
src/GPU2DSoft.cpp:684:12: warning: suggest explicit braces to avoid ambiguous 'else' [-Wdangling-else]
         if ((DispCnt & 0x1000) && NumSprites)
            ^
src/GPU2DSoft.cpp: In member function 'void GPU2DSoft::DrawScanlineBGMode7(u32)':
src/GPU2DSoft.cpp:712:12: warning: suggest explicit braces to avoid ambiguous 'else' [-Wdangling-else]
         if ((DispCnt & 0x1000) && NumSprites)
            ^
src/GPU2DSoft.cpp: In member function 'void GPU2DSoft::DrawScanline_BGOBJ(u32)':
src/GPU2DSoft.cpp:741:14: warning: dereferencing type-punned pointer will break strict-aliasing rules [-Wstrict-aliasing]
             *(u64*)&BGOBJLine[i] = backdrop;
              ^~~~~~~~~~~~~~~~~~~
src/GPU2DSoft.cpp:825:30: warning: variable 'evb' set but not used [-Wunused-but-set-variable]
                     u32 eva, evb;
                              ^~~
src/GPU2DSoft.cpp: In member function 'virtual void GPU2DSoft::DrawSprites(u32)':
src/GPU2DSoft.cpp:1716:21: warning: unused variable 'rotparamgroup' [-Wunused-variable]
                 u32 rotparamgroup = (attrib[1] >> 9) & 0x1F;
                     ^~~~~~~~~~~~~
src/GPU2DSoft.cpp: In instantiation of 'void GPU2DSoft::DrawBG_Large(u32) [with bool mosaic = true; void (* drawPixel)(u32*, u16, u32) = GPU2DSoft::DrawPixel_Accel; u32 = unsigned int]':
src/GPU2DSoft.cpp:673:17:   required from here
src/GPU2DSoft.cpp:1444:9: warning: unused variable 'tilesetaddr' [-Wunused-variable]
     u32 tilesetaddr, tilemapaddr;
         ^~~~~~~~~~~
src/GPU2DSoft.cpp: In instantiation of 'void GPU2DSoft::DrawBG_Large(u32) [with bool mosaic = true; void (* drawPixel)(u32*, u16, u32) = GPU2DSoft::DrawPixel_Normal; u32 = unsigned int]':
src/GPU2DSoft.cpp:673:17:   required from here
src/GPU2DSoft.cpp:1444:9: warning: unused variable 'tilesetaddr' [-Wunused-variable]
src/GPU2DSoft.cpp: In instantiation of 'void GPU2DSoft::DrawBG_Large(u32) [with bool mosaic = false; void (* drawPixel)(u32*, u16, u32) = GPU2DSoft::DrawPixel_Accel; u32 = unsigned int]':
src/GPU2DSoft.cpp:673:17:   required from here
src/GPU2DSoft.cpp:1444:9: warning: unused variable 'tilesetaddr' [-Wunused-variable]
src/GPU2DSoft.cpp: In instantiation of 'void GPU2DSoft::DrawBG_Large(u32) [with bool mosaic = false; void (* drawPixel)(u32*, u16, u32) = GPU2DSoft::DrawPixel_Normal; u32 = unsigned int]':
src/GPU2DSoft.cpp:673:17:   required from here
src/GPU2DSoft.cpp:1444:9: warning: unused variable 'tilesetaddr' [-Wunused-variable]
src/GPU2DSoft.cpp: In instantiation of 'void GPU2DSoft::DrawSprite_Normal(u32, u32, u32, s32, s32) [with bool window = true; u32 = unsigned int; s32 = int]':
src/GPU2DSoft.cpp:1740:17:   required from here
src/GPU2DSoft.cpp:2052:33: warning: suggest parentheses around '-' inside '<<' [-Wparentheses]
             pixelsaddr += (width-1 << 1);
                            ~~~~~^~
src/GPU2DSoft.cpp:2162:17: warning: variable 'pixelstride' set but not used [-Wunused-but-set-variable]
             s32 pixelstride;
                 ^~~~~~~~~~~
src/GPU2DSoft.cpp: In instantiation of 'void GPU2DSoft::DrawSprite_Normal(u32, u32, u32, s32, s32) [with bool window = false; u32 = unsigned int; s32 = int]':
src/GPU2DSoft.cpp:1740:17:   required from here
src/GPU2DSoft.cpp:2052:33: warning: suggest parentheses around '-' inside '<<' [-Wparentheses]
             pixelsaddr += (width-1 << 1);
                            ~~~~~^~
src/GPU2DSoft.cpp:2162:17: warning: variable 'pixelstride' set but not used [-Wunused-but-set-variable]
             s32 pixelstride;
                 ^~~~~~~~~~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/GPU3D.o src/GPU3D.cpp
src/GPU2DSoft.cpp: In member function 'u32 GPU2DSoft::ColorComposite(int, u32, u32)':
src/GPU2DSoft.cpp:27:62: warning: 'evb' may be used uninitialized in this function [-Wmaybe-uninitialized]
     u32 b = ((((val1 & 0x3F0000) * eva) + ((val2 & 0x3F0000) * evb)) >> 4) & 0x7F0000;
                                           ~~~~~~~~~~~~~~~~~~~^~~~~~
src/GPU2DSoft.cpp:86:14: note: 'evb' was declared here
     u32 eva, evb;
              ^~~
src/GPU2DSoft.cpp:27:34: warning: 'eva' may be used uninitialized in this function [-Wmaybe-uninitialized]
     u32 b = ((((val1 & 0x3F0000) * eva) + ((val2 & 0x3F0000) * evb)) >> 4) & 0x7F0000;
               ~~~~~~~~~~~~~~~~~~~^~~~~~
src/GPU2DSoft.cpp:86:9: note: 'eva' was declared here
     u32 eva, evb;
         ^~~
src/GPU3D.cpp: In function 'void GPU3D::DoSavestate(Savestate*)':
src/GPU3D.cpp:492:16: warning: comparison of integer expressions of different signedness: 'u32' {aka 'unsigned int'} and 'int' [-Wsign-compare]
         if (id == -1) LastStripPolygon = NULL;
             ~~~^~~~~
src/GPU3D.cpp:541:24: warning: comparison of integer expressions of different signedness: 'u32' {aka 'unsigned int'} and 'int' [-Wsign-compare]
                 if (id == -1) poly->Vertices[j] = NULL;
                     ~~~^~~~~
src/GPU3D.cpp:580:31: warning: comparison of integer expressions of different signedness: 'int' and 'u32' {aka 'unsigned int'} [-Wsign-compare]
             for (int j = 0; j < poly->NumVertices; j++)
                             ~~^~~~~~~~~~~~~~~~~~~
src/GPU3D.cpp: In function 'void GPU3D::SubmitPolygon()':
src/GPU3D.cpp:1098:43: warning: comparison of integer expressions of different signedness: 'u32' {aka 'unsigned int'} and 'int' [-Wsign-compare]
         if (LastStripPolygon->NumVertices == lastpolyverts &&
             ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~
src/GPU2DSoft.cpp: In member function 'void GPU2DSoft::DrawScanlineBGMode6(u32)':
src/GPU2DSoft.cpp:1444:22: warning: 'tilemapaddr' may be used uninitialized in this function [-Wmaybe-uninitialized]
     u32 tilesetaddr, tilemapaddr;
                      ^~~~~~~~~~~
src/GPU2DSoft.cpp:1444:22: warning: 'tilemapaddr' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1444:22: warning: 'tilemapaddr' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1444:22: warning: 'tilemapaddr' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1519:72: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                               ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1453:9: note: 'yshift' was declared here
     u32 yshift;
         ^~~~~~
src/GPU2DSoft.cpp:1519:57: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                 ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1452:16: note: 'ymask' was declared here
     u32 xmask, ymask;
                ^~~~~
src/GPU2DSoft.cpp:1519:94: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                                                      ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1452:9: note: 'xmask' was declared here
     u32 xmask, ymask;
         ^~~~~
src/GPU2DSoft.cpp:1519:72: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                               ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1453:9: note: 'yshift' was declared here
     u32 yshift;
         ^~~~~~
src/GPU2DSoft.cpp:1519:57: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                 ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1452:16: note: 'ymask' was declared here
     u32 xmask, ymask;
                ^~~~~
src/GPU2DSoft.cpp:1519:94: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                                                      ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1452:9: note: 'xmask' was declared here
     u32 xmask, ymask;
         ^~~~~
src/GPU2DSoft.cpp:1519:72: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                               ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1453:9: note: 'yshift' was declared here
     u32 yshift;
         ^~~~~~
src/GPU2DSoft.cpp:1519:57: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                 ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1452:16: note: 'ymask' was declared here
     u32 xmask, ymask;
                ^~~~~
src/GPU2DSoft.cpp:1519:94: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                                                      ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1452:9: note: 'xmask' was declared here
     u32 xmask, ymask;
         ^~~~~
src/GPU2DSoft.cpp:1519:72: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                               ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1453:9: note: 'yshift' was declared here
     u32 yshift;
         ^~~~~~
src/GPU2DSoft.cpp:1519:57: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                 ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1452:16: note: 'ymask' was declared here
     u32 xmask, ymask;
                ^~~~~
src/GPU2DSoft.cpp:1519:94: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                                                      ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1452:9: note: 'xmask' was declared here
     u32 xmask, ymask;
         ^~~~~
src/GPU3D.cpp:1225:34: warning: comparison of integer expressions of different signedness: 's32' {aka 'int'} and 'u32' {aka 'unsigned int'} [-Wsign-compare]
             if (vtx->Position[3] <= ZeroDotWLimit)
                 ~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~
src/GPU3D.cpp:1009:9: warning: unused variable 'prev' [-Wunused-variable]
     int prev, next;
         ^~~~
src/GPU3D.cpp:1009:15: warning: unused variable 'next' [-Wunused-variable]
     int prev, next;
               ^~~~
src/GPU3D.cpp:1022:28: warning: variable 'v3' set but not used [-Wunused-but-set-variable]
     Vertex *v0, *v1, *v2, *v3;
                            ^~
src/GPU2DSoft.cpp: In member function 'void GPU2DSoft::DrawBG_Text(u32, u32) [with bool mosaic = false; void (* drawPixel)(u32*, u16, u32) = GPU2DSoft::DrawPixel_Accel]':
src/GPU2DSoft.cpp:1006:9: warning: 'pixelsaddr' may be used uninitialized in this function [-Wmaybe-uninitialized]
     u32 pixelsaddr;
         ^~~~~~~~~~
src/GPU2DSoft.cpp:1109:30: warning: 'curpal' may be used uninitialized in this function [-Wmaybe-uninitialized]
                     drawPixel(&BGOBJLine[i], curpal[color], 0x01000000<<bgnum);
                     ~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
src/GPU2DSoft.cpp:1004:9: warning: 'curtile' may be used uninitialized in this function [-Wmaybe-uninitialized]
     u16 curtile;
         ^~~~~~~
src/GPU2DSoft.cpp: In member function 'void GPU2DSoft::DrawBG_Text(u32, u32) [with bool mosaic = false; void (* drawPixel)(u32*, u16, u32) = GPU2DSoft::DrawPixel_Normal]':
src/GPU2DSoft.cpp:1006:9: warning: 'pixelsaddr' may be used uninitialized in this function [-Wmaybe-uninitialized]
     u32 pixelsaddr;
         ^~~~~~~~~~
src/GPU2DSoft.cpp:1109:30: warning: 'curpal' may be used uninitialized in this function [-Wmaybe-uninitialized]
                     drawPixel(&BGOBJLine[i], curpal[color], 0x01000000<<bgnum);
                     ~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
src/GPU2DSoft.cpp:1004:9: warning: 'curtile' may be used uninitialized in this function [-Wmaybe-uninitialized]
     u16 curtile;
         ^~~~~~~
src/GPU2DSoft.cpp: In member function 'void GPU2DSoft::DrawScanlineBGMode(u32) [with unsigned int bgmode = 1]':
src/GPU2DSoft.cpp:1126:9: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
     u32 yshift;
         ^~~~~~
src/GPU2DSoft.cpp:1126:9: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1126:9: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1126:9: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1197:102: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 curtile = bgvram[(tilemapaddr + ((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11))) & bgvrammask];
                                                                                              ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1125:9: note: 'coordmask' was declared here
     u32 coordmask;
         ^~~~~~~~~
src/GPU2DSoft.cpp:1197:102: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 curtile = bgvram[(tilemapaddr + ((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11))) & bgvrammask];
                                                                                              ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1125:9: note: 'coordmask' was declared here
     u32 coordmask;
         ^~~~~~~~~
src/GPU2DSoft.cpp:1197:102: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 curtile = bgvram[(tilemapaddr + ((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11))) & bgvrammask];
                                                                                              ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1125:9: note: 'coordmask' was declared here
     u32 coordmask;
         ^~~~~~~~~
src/GPU2DSoft.cpp:1197:102: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 curtile = bgvram[(tilemapaddr + ((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11))) & bgvrammask];
                                                                                              ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1125:9: note: 'coordmask' was declared here
     u32 coordmask;
         ^~~~~~~~~
src/GPU2DSoft.cpp: In member function 'void GPU2DSoft::DrawScanlineBGMode(u32) [with unsigned int bgmode = 2]':
src/GPU2DSoft.cpp:1126:9: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
     u32 yshift;
         ^~~~~~
src/GPU2DSoft.cpp:1126:9: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1126:9: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1126:9: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1126:9: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1126:9: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1126:9: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1126:9: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1197:102: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 curtile = bgvram[(tilemapaddr + ((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11))) & bgvrammask];
                                                                                              ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1125:9: note: 'coordmask' was declared here
     u32 coordmask;
         ^~~~~~~~~
src/GPU2DSoft.cpp:1197:102: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 curtile = bgvram[(tilemapaddr + ((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11))) & bgvrammask];
                                                                                              ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1125:9: note: 'coordmask' was declared here
     u32 coordmask;
         ^~~~~~~~~
src/GPU2DSoft.cpp:1197:102: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 curtile = bgvram[(tilemapaddr + ((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11))) & bgvrammask];
                                                                                              ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1125:9: note: 'coordmask' was declared here
     u32 coordmask;
         ^~~~~~~~~
src/GPU2DSoft.cpp:1197:102: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 curtile = bgvram[(tilemapaddr + ((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11))) & bgvrammask];
                                                                                              ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1125:9: note: 'coordmask' was declared here
     u32 coordmask;
         ^~~~~~~~~
src/GPU2DSoft.cpp:1197:102: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 curtile = bgvram[(tilemapaddr + ((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11))) & bgvrammask];
                                                                                              ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1125:9: note: 'coordmask' was declared here
     u32 coordmask;
         ^~~~~~~~~
src/GPU2DSoft.cpp:1197:102: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 curtile = bgvram[(tilemapaddr + ((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11))) & bgvrammask];
                                                                                              ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1125:9: note: 'coordmask' was declared here
     u32 coordmask;
         ^~~~~~~~~
src/GPU2DSoft.cpp:1197:102: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 curtile = bgvram[(tilemapaddr + ((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11))) & bgvrammask];
                                                                                              ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1125:9: note: 'coordmask' was declared here
     u32 coordmask;
         ^~~~~~~~~
src/GPU2DSoft.cpp:1197:102: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 curtile = bgvram[(tilemapaddr + ((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11))) & bgvrammask];
                                                                                              ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1125:9: note: 'coordmask' was declared here
     u32 coordmask;
         ^~~~~~~~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/GPU3D_Soft.o src/GPU3D_Soft.cpp
src/GPU2DSoft.cpp: In member function 'void GPU2DSoft::DrawScanlineBGMode(u32) [with unsigned int bgmode = 3]':
src/GPU2DSoft.cpp:1358:13: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1358:13: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1358:13: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1358:13: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1369:56: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
         else                overflowmask = ~(coordmask | 0x7FF);
                                             ~~~~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1357:13: note: 'coordmask' was declared here
         u32 coordmask;
             ^~~~~~~~~
src/GPU2DSoft.cpp:1341:80: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                       ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1253:13: note: 'yshift' was declared here
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1271:13: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
             ofymask = ~ymask;
             ^~~~~~~
src/GPU2DSoft.cpp:1252:20: note: 'ymask' was declared here
         u32 xmask, ymask;
                    ^~~~~
src/GPU2DSoft.cpp:1270:13: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
             ofxmask = ~xmask;
             ^~~~~~~
src/GPU2DSoft.cpp:1252:13: note: 'xmask' was declared here
         u32 xmask, ymask;
             ^~~~~
src/GPU2DSoft.cpp:1369:56: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
         else                overflowmask = ~(coordmask | 0x7FF);
                                             ~~~~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1357:13: note: 'coordmask' was declared here
         u32 coordmask;
             ^~~~~~~~~
src/GPU2DSoft.cpp:1341:80: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                       ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1253:13: note: 'yshift' was declared here
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1271:13: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
             ofymask = ~ymask;
             ^~~~~~~
src/GPU2DSoft.cpp:1252:20: note: 'ymask' was declared here
         u32 xmask, ymask;
                    ^~~~~
src/GPU2DSoft.cpp:1270:13: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
             ofxmask = ~xmask;
             ^~~~~~~
src/GPU2DSoft.cpp:1252:13: note: 'xmask' was declared here
         u32 xmask, ymask;
             ^~~~~
src/GPU2DSoft.cpp:1411:115: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                     curtile = *(u16*)&bgvram[(tilemapaddr + (((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11)) << 1)) & bgvrammask];
                                                                                                           ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1357:13: note: 'coordmask' was declared here
         u32 coordmask;
             ^~~~~~~~~
src/GPU2DSoft.cpp:1341:80: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                       ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1253:13: note: 'yshift' was declared here
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1302:75: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = *(u16*)&bgvram[(tilemapaddr + (((((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) << 1)) & bgvrammask];
                                                                   ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1252:20: note: 'ymask' was declared here
         u32 xmask, ymask;
                    ^~~~~
src/GPU2DSoft.cpp:1302:112: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = *(u16*)&bgvram[(tilemapaddr + (((((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) << 1)) & bgvrammask];
                                                                                                        ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1252:13: note: 'xmask' was declared here
         u32 xmask, ymask;
             ^~~~~
src/GPU2DSoft.cpp:1411:115: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                     curtile = *(u16*)&bgvram[(tilemapaddr + (((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11)) << 1)) & bgvrammask];
                                                                                                           ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1357:13: note: 'coordmask' was declared here
         u32 coordmask;
             ^~~~~~~~~
src/GPU2DSoft.cpp:1341:80: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                       ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1253:13: note: 'yshift' was declared here
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1302:75: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = *(u16*)&bgvram[(tilemapaddr + (((((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) << 1)) & bgvrammask];
                                                                   ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1252:20: note: 'ymask' was declared here
         u32 xmask, ymask;
                    ^~~~~
src/GPU2DSoft.cpp:1302:112: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = *(u16*)&bgvram[(tilemapaddr + (((((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) << 1)) & bgvrammask];
                                                                                                        ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1252:13: note: 'xmask' was declared here
         u32 xmask, ymask;
             ^~~~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/NDSCart.o src/NDSCart.cpp
src/GPU3D_Soft.cpp: In function 'void GPU3D::SoftRenderer::PlotTranslucentPixel(u32, u32, u32, u32, u32)':
src/GPU3D_Soft.cpp:1012:11: warning: comparison of integer expressions of different signedness: 'u32' {aka 'unsigned int'} and 'int' [-Wsign-compare]
     if (z != -1)
         ~~^~~~~
src/GPU3D_Soft.cpp: In function 'void GPU3D::SoftRenderer::RenderShadowMaskScanline(GPU3D::SoftRenderer::RendererPolygon*, s32)':
src/GPU3D_Soft.cpp:1162:13: warning: variable 'vlcur' set but not used [-Wunused-but-set-variable]
     Vertex *vlcur, *vlnext, *vrcur, *vrnext;
             ^~~~~
src/GPU3D_Soft.cpp:1162:21: warning: variable 'vlnext' set but not used [-Wunused-but-set-variable]
     Vertex *vlcur, *vlnext, *vrcur, *vrnext;
                     ^~~~~~
src/GPU3D_Soft.cpp:1162:30: warning: variable 'vrcur' set but not used [-Wunused-but-set-variable]
     Vertex *vlcur, *vlnext, *vrcur, *vrnext;
                              ^~~~~
src/GPU3D_Soft.cpp:1162:38: warning: variable 'vrnext' set but not used [-Wunused-but-set-variable]
     Vertex *vlcur, *vlnext, *vrcur, *vrnext;
                                      ^~~~~~
src/GPU3D_Soft.cpp:1167:22: warning: variable 'interp_start' set but not used [-Wunused-but-set-variable]
     Interpolator<1>* interp_start;
                      ^~~~~~~~~~~~
src/GPU3D_Soft.cpp:1168:22: warning: variable 'interp_end' set but not used [-Wunused-but-set-variable]
     Interpolator<1>* interp_end;
                      ^~~~~~~~~~
src/NDSCart.cpp: In function 'bool NDSCart::LoadROM(const char*, const char*, bool)':
src/NDSCart.cpp:985:24: warning: 'char* strncpy(char*, const char*, size_t)' output truncated before terminating nul copying 8 bytes from a string of the same length [-Wstringop-truncation]
                 strncpy((char*)&CartROM[arm9base], "encryObj", 8);
                 ~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
src/GPU2DSoft.cpp: In member function 'void GPU2DSoft::DrawScanlineBGMode(u32) [with unsigned int bgmode = 4]':
src/GPU2DSoft.cpp:1358:13: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1358:13: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1358:13: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1358:13: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1126:9: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
     u32 yshift;
         ^~~~~~
src/GPU2DSoft.cpp:1126:9: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1126:9: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1126:9: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1197:102: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 curtile = bgvram[(tilemapaddr + ((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11))) & bgvrammask];
                                                                                              ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1125:9: note: 'coordmask' was declared here
     u32 coordmask;
         ^~~~~~~~~
src/GPU2DSoft.cpp:1197:102: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 curtile = bgvram[(tilemapaddr + ((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11))) & bgvrammask];
                                                                                              ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1125:9: note: 'coordmask' was declared here
     u32 coordmask;
         ^~~~~~~~~
src/GPU2DSoft.cpp:1197:102: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 curtile = bgvram[(tilemapaddr + ((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11))) & bgvrammask];
                                                                                              ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1125:9: note: 'coordmask' was declared here
     u32 coordmask;
         ^~~~~~~~~
src/GPU2DSoft.cpp:1197:102: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 curtile = bgvram[(tilemapaddr + ((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11))) & bgvrammask];
                                                                                              ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1125:9: note: 'coordmask' was declared here
     u32 coordmask;
         ^~~~~~~~~
src/GPU2DSoft.cpp:1369:56: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
         else                overflowmask = ~(coordmask | 0x7FF);
                                             ~~~~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1357:13: note: 'coordmask' was declared here
         u32 coordmask;
             ^~~~~~~~~
src/GPU2DSoft.cpp:1341:80: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                       ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1253:13: note: 'yshift' was declared here
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1271:13: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
             ofymask = ~ymask;
             ^~~~~~~
src/GPU2DSoft.cpp:1252:20: note: 'ymask' was declared here
         u32 xmask, ymask;
                    ^~~~~
src/GPU2DSoft.cpp:1270:13: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
             ofxmask = ~xmask;
             ^~~~~~~
src/GPU2DSoft.cpp:1252:13: note: 'xmask' was declared here
         u32 xmask, ymask;
             ^~~~~
src/GPU2DSoft.cpp:1369:56: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
         else                overflowmask = ~(coordmask | 0x7FF);
                                             ~~~~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1357:13: note: 'coordmask' was declared here
         u32 coordmask;
             ^~~~~~~~~
src/GPU2DSoft.cpp:1341:80: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                       ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1253:13: note: 'yshift' was declared here
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1271:13: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
             ofymask = ~ymask;
             ^~~~~~~
src/GPU2DSoft.cpp:1252:20: note: 'ymask' was declared here
         u32 xmask, ymask;
                    ^~~~~
src/GPU2DSoft.cpp:1270:13: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
             ofxmask = ~xmask;
             ^~~~~~~
src/GPU2DSoft.cpp:1252:13: note: 'xmask' was declared here
         u32 xmask, ymask;
             ^~~~~
src/GPU2DSoft.cpp:1411:115: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                     curtile = *(u16*)&bgvram[(tilemapaddr + (((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11)) << 1)) & bgvrammask];
                                                                                                           ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1357:13: note: 'coordmask' was declared here
         u32 coordmask;
             ^~~~~~~~~
src/GPU2DSoft.cpp:1341:80: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                       ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1253:13: note: 'yshift' was declared here
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1302:75: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = *(u16*)&bgvram[(tilemapaddr + (((((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) << 1)) & bgvrammask];
                                                                   ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1252:20: note: 'ymask' was declared here
         u32 xmask, ymask;
                    ^~~~~
src/GPU2DSoft.cpp:1302:112: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = *(u16*)&bgvram[(tilemapaddr + (((((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) << 1)) & bgvrammask];
                                                                                                        ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1252:13: note: 'xmask' was declared here
         u32 xmask, ymask;
             ^~~~~
src/GPU2DSoft.cpp:1411:115: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                     curtile = *(u16*)&bgvram[(tilemapaddr + (((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11)) << 1)) & bgvrammask];
                                                                                                           ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1357:13: note: 'coordmask' was declared here
         u32 coordmask;
             ^~~~~~~~~
src/GPU2DSoft.cpp:1341:80: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                       ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1253:13: note: 'yshift' was declared here
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1302:75: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = *(u16*)&bgvram[(tilemapaddr + (((((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) << 1)) & bgvrammask];
                                                                   ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1252:20: note: 'ymask' was declared here
         u32 xmask, ymask;
                    ^~~~~
src/GPU2DSoft.cpp:1302:112: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = *(u16*)&bgvram[(tilemapaddr + (((((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) << 1)) & bgvrammask];
                                                                                                        ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1252:13: note: 'xmask' was declared here
         u32 xmask, ymask;
             ^~~~~
src/GPU3D.cpp:1284:31: warning: 'reusedvertices[1]' may be used uninitialized in this function [-Wmaybe-uninitialized]
             poly->Vertices[1] = reusedvertices[1];
             ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~
src/GPU3D.cpp:1283:31: warning: 'reusedvertices[0]' may be used uninitialized in this function [-Wmaybe-uninitialized]
             poly->Vertices[0] = reusedvertices[0];
             ~~~~~~~~~~~~~~~~~~^~~~~~~~~~~~~~~~~~~
src/GPU3D_Soft.cpp:281:46: warning: 'interpX.GPU3D::SoftRenderer::Interpolator<0>::yfactor' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 return z0 + (((s64)(z1-z0) * yfactor) >> shift);
                                              ^~~~~~~
src/GPU3D_Soft.cpp:1242:21: note: 'interpX.GPU3D::SoftRenderer::Interpolator<0>::yfactor' was declared here
     Interpolator<0> interpX(xstart, xend+1, wl, wr);
                     ^~~~~~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/RTC.o src/RTC.cpp
src/GPU2DSoft.cpp: In member function 'void GPU2DSoft::DrawScanlineBGMode(u32) [with unsigned int bgmode = 5]':
src/GPU2DSoft.cpp:1358:13: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1358:13: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1358:13: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1358:13: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1358:13: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1358:13: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1358:13: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1358:13: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
src/GPU2DSoft.cpp:1369:56: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
         else                overflowmask = ~(coordmask | 0x7FF);
                                             ~~~~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1357:13: note: 'coordmask' was declared here
         u32 coordmask;
             ^~~~~~~~~
src/GPU2DSoft.cpp:1341:80: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                       ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1253:13: note: 'yshift' was declared here
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1271:13: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
             ofymask = ~ymask;
             ^~~~~~~
src/GPU2DSoft.cpp:1252:20: note: 'ymask' was declared here
         u32 xmask, ymask;
                    ^~~~~
src/GPU2DSoft.cpp:1270:13: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
             ofxmask = ~xmask;
             ^~~~~~~
src/GPU2DSoft.cpp:1252:13: note: 'xmask' was declared here
         u32 xmask, ymask;
             ^~~~~
src/GPU2DSoft.cpp:1369:56: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
         else                overflowmask = ~(coordmask | 0x7FF);
                                             ~~~~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1357:13: note: 'coordmask' was declared here
         u32 coordmask;
             ^~~~~~~~~
src/GPU2DSoft.cpp:1341:80: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                       ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1253:13: note: 'yshift' was declared here
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1271:13: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
             ofymask = ~ymask;
             ^~~~~~~
src/GPU2DSoft.cpp:1252:20: note: 'ymask' was declared here
         u32 xmask, ymask;
                    ^~~~~
src/GPU2DSoft.cpp:1270:13: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
             ofxmask = ~xmask;
             ^~~~~~~
src/GPU2DSoft.cpp:1252:13: note: 'xmask' was declared here
         u32 xmask, ymask;
             ^~~~~
src/GPU2DSoft.cpp:1411:115: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                     curtile = *(u16*)&bgvram[(tilemapaddr + (((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11)) << 1)) & bgvrammask];
                                                                                                           ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1357:13: note: 'coordmask' was declared here
         u32 coordmask;
             ^~~~~~~~~
src/GPU2DSoft.cpp:1341:80: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                       ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1253:13: note: 'yshift' was declared here
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1302:75: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = *(u16*)&bgvram[(tilemapaddr + (((((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) << 1)) & bgvrammask];
                                                                   ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1252:20: note: 'ymask' was declared here
         u32 xmask, ymask;
                    ^~~~~
src/GPU2DSoft.cpp:1302:112: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = *(u16*)&bgvram[(tilemapaddr + (((((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) << 1)) & bgvrammask];
                                                                                                        ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1252:13: note: 'xmask' was declared here
         u32 xmask, ymask;
             ^~~~~
src/GPU2DSoft.cpp:1411:115: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                     curtile = *(u16*)&bgvram[(tilemapaddr + (((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11)) << 1)) & bgvrammask];
                                                                                                           ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1357:13: note: 'coordmask' was declared here
         u32 coordmask;
             ^~~~~~~~~
src/GPU2DSoft.cpp:1341:80: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                       ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1253:13: note: 'yshift' was declared here
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1302:75: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = *(u16*)&bgvram[(tilemapaddr + (((((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) << 1)) & bgvrammask];
                                                                   ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1252:20: note: 'ymask' was declared here
         u32 xmask, ymask;
                    ^~~~~
src/GPU2DSoft.cpp:1302:112: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = *(u16*)&bgvram[(tilemapaddr + (((((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) << 1)) & bgvrammask];
                                                                                                        ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1252:13: note: 'xmask' was declared here
         u32 xmask, ymask;
             ^~~~~
src/GPU2DSoft.cpp:1369:56: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
         else                overflowmask = ~(coordmask | 0x7FF);
                                             ~~~~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1357:13: note: 'coordmask' was declared here
         u32 coordmask;
             ^~~~~~~~~
src/GPU2DSoft.cpp:1341:80: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                       ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1253:13: note: 'yshift' was declared here
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1271:13: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
             ofymask = ~ymask;
             ^~~~~~~
src/GPU2DSoft.cpp:1252:20: note: 'ymask' was declared here
         u32 xmask, ymask;
                    ^~~~~
src/GPU2DSoft.cpp:1270:13: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
             ofxmask = ~xmask;
             ^~~~~~~
src/GPU2DSoft.cpp:1252:13: note: 'xmask' was declared here
         u32 xmask, ymask;
             ^~~~~
src/GPU2DSoft.cpp:1369:56: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
         else                overflowmask = ~(coordmask | 0x7FF);
                                             ~~~~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1357:13: note: 'coordmask' was declared here
         u32 coordmask;
             ^~~~~~~~~
src/GPU2DSoft.cpp:1341:80: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                       ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1253:13: note: 'yshift' was declared here
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1271:13: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
             ofymask = ~ymask;
             ^~~~~~~
src/GPU2DSoft.cpp:1252:20: note: 'ymask' was declared here
         u32 xmask, ymask;
                    ^~~~~
src/GPU2DSoft.cpp:1270:13: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
             ofxmask = ~xmask;
             ^~~~~~~
src/GPU2DSoft.cpp:1252:13: note: 'xmask' was declared here
         u32 xmask, ymask;
             ^~~~~
src/GPU2DSoft.cpp:1411:115: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                     curtile = *(u16*)&bgvram[(tilemapaddr + (((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11)) << 1)) & bgvrammask];
                                                                                                           ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1357:13: note: 'coordmask' was declared here
         u32 coordmask;
             ^~~~~~~~~
src/GPU2DSoft.cpp:1341:80: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                       ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1253:13: note: 'yshift' was declared here
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1302:75: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = *(u16*)&bgvram[(tilemapaddr + (((((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) << 1)) & bgvrammask];
                                                                   ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1252:20: note: 'ymask' was declared here
         u32 xmask, ymask;
                    ^~~~~
src/GPU2DSoft.cpp:1302:112: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = *(u16*)&bgvram[(tilemapaddr + (((((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) << 1)) & bgvrammask];
                                                                                                        ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1252:13: note: 'xmask' was declared here
         u32 xmask, ymask;
             ^~~~~
src/GPU2DSoft.cpp:1411:115: warning: 'coordmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                     curtile = *(u16*)&bgvram[(tilemapaddr + (((((finalY & coordmask) >> 11) << yshift) + ((finalX & coordmask) >> 11)) << 1)) & bgvrammask];
                                                                                                           ~~~~~~~~^~~~~~~~~~~~
src/GPU2DSoft.cpp:1357:13: note: 'coordmask' was declared here
         u32 coordmask;
             ^~~~~~~~~
src/GPU2DSoft.cpp:1341:80: warning: 'yshift' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = bgvram[(tilemapaddr + (((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) & bgvrammask];
                                                       ~~~~~~~~~~~~~~~~~~~~~~~~~^~~~~~~~~~
src/GPU2DSoft.cpp:1253:13: note: 'yshift' was declared here
         u32 yshift;
             ^~~~~~
src/GPU2DSoft.cpp:1302:75: warning: 'ymask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = *(u16*)&bgvram[(tilemapaddr + (((((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) << 1)) & bgvrammask];
                                                                   ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1252:20: note: 'ymask' was declared here
         u32 xmask, ymask;
                    ^~~~~
src/GPU2DSoft.cpp:1302:112: warning: 'xmask' may be used uninitialized in this function [-Wmaybe-uninitialized]
                         color = *(u16*)&bgvram[(tilemapaddr + (((((finalY & ymask) >> 8) << yshift) + ((finalX & xmask) >> 8)) << 1)) & bgvrammask];
                                                                                                        ~~~~~~~~^~~~~~~~
src/GPU2DSoft.cpp:1252:13: note: 'xmask' was declared here
         u32 xmask, ymask;
             ^~~~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/Savestate.o src/Savestate.cpp
src/GPU3D_Soft.cpp: In function 'void GPU3D::SoftRenderer::RenderPolygonScanline(GPU3D::SoftRenderer::RendererPolygon*, s32)':
src/GPU3D_Soft.cpp:281:46: warning: 'interpX.GPU3D::SoftRenderer::Interpolator<0>::yfactor' may be used uninitialized in this function [-Wmaybe-uninitialized]
                 return z0 + (((s64)(z1-z0) * yfactor) >> shift);
                                              ^~~~~~~
src/GPU3D_Soft.cpp:1471:21: note: 'interpX.GPU3D::SoftRenderer::Interpolator<0>::yfactor' was declared here
     Interpolator<0> interpX(xstart, xend+1, wl, wr);
                     ^~~~~~~
src/Savestate.cpp:24: warning: "fclose" redefined
 #define fclose(stream) memstream_close(stream)
 
In file included from src/Savestate.cpp:21:
src/Platform.h:28: note: this is the location of the previous definition
 #define fclose rfclose
 
src/Savestate.cpp:25: warning: "fread" redefined
 #define fread(data, len, count, stream) memstream_read(stream, data, len)
 
In file included from src/Savestate.cpp:21:
src/Platform.h:29: note: this is the location of the previous definition
 #define fread rfread
 
src/Savestate.cpp:26: warning: "fwrite" redefined
 #define fwrite(data, len, count, stream) memstream_write(stream, data, len)
 
In file included from src/Platform.h:26,
                 from src/Savestate.cpp:21:
./src/libretro/libretro-common/include/streams/file_stream_transforms.h:59: note: this is the location of the previous definition
 #define fwrite rfwrite
 
src/Savestate.cpp:27: warning: "fseek" redefined
 #define fseek(stream, offset, mask) memstream_seek(stream, offset, mask)
 
In file included from src/Savestate.cpp:21:
src/Platform.h:30: note: this is the location of the previous definition
 #define fseek rfseek
 
src/Savestate.cpp:28: warning: "ftell" redefined
 #define ftell(stream) memstream_pos(stream)
 
In file included from src/Platform.h:26,
                 from src/Savestate.cpp:21:
./src/libretro/libretro-common/include/streams/file_stream_transforms.h:54: note: this is the location of the previous definition
 #define ftell rftell
 
src/Savestate.cpp: In destructor 'Savestate::~Savestate()':
src/Savestate.cpp:171:24: warning: comparison of integer expressions of different signedness: 'u32' {aka 'unsigned int'} and 'int' [-Wsign-compare]
         if (CurSection != -1)
             ~~~~~~~~~~~^~~~~
src/Savestate.cpp: In member function 'void Savestate::Section(const char*)':
src/Savestate.cpp:197:24: warning: comparison of integer expressions of different signedness: 'u32' {aka 'unsigned int'} and 'int' [-Wsign-compare]
         if (CurSection != -1)
             ~~~~~~~~~~~^~~~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/SPI.o src/SPI.cpp
src/SPI.cpp: In function 'void SPI_TSC::Write(u8, u32)':
src/SPI.cpp:574:35: warning: comparison of integer expressions of different signedness: 'u32' {aka 'unsigned int'} and 'int' [-Wsign-compare]
                     if (samplepos >= MicBufferLen) samplepos = MicBufferLen-1;
                         ~~~~~~~~~~^~~~~~~~~~~~~~~
src/SPI.cpp: In function 'void SPI_Firmware::Reset()':
src/SPI.cpp:99:16: warning: 'char* strncpy(char*, const char*, size_t)' output may be truncated copying 1023 bytes from a string of length 1023 [-Wstringop-truncation]
         strncpy(FirmwarePath, Config::FirmwarePath, 1023);
         ~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
src/SPI.cpp:97:16: warning: 'char* strncpy(char*, const char*, size_t)' output may be truncated copying 1023 bytes from a string of length 1023 [-Wstringop-truncation]
         strncpy(FirmwarePath, Config::DSiFirmwarePath, 1023);
         ~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
src/SPI.cpp:142:12: warning: 'char* strncpy(char*, const char*, size_t)' output truncated before terminating nul copying as many bytes from a string as its length [-Wstringop-truncation]
     strncpy(&firmbkp[0], FirmwarePath, fplen);
     ~~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
src/SPI.cpp:141:23: note: length computed here
     int fplen = strlen(FirmwarePath);
                 ~~~~~~^~~~~~~~~~~~~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/SPU.o src/SPU.cpp
src/SPU.cpp: In member function 'void SPU::Channel::NextSample_PCM8()':
src/SPU.cpp:291:13: warning: comparison of integer expressions of different signedness: 's32' {aka 'int'} and 'u32' {aka 'unsigned int'} [-Wsign-compare]
     if (Pos >= (LoopPos + Length))
         ~~~~^~~~~~~~~~~~~~~~~~~~~
src/SPU.cpp: In member function 'void SPU::Channel::NextSample_PCM16()':
src/SPU.cpp:314:18: warning: comparison of integer expressions of different signedness: 's32' {aka 'int'} and 'u32' {aka 'unsigned int'} [-Wsign-compare]
     if ((Pos<<1) >= (LoopPos + Length))
         ~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~
src/SPU.cpp: In member function 'void SPU::Channel::NextSample_ADPCM()':
src/SPU.cpp:353:18: warning: comparison of integer expressions of different signedness: 's32' {aka 'int'} and 'u32' {aka 'unsigned int'} [-Wsign-compare]
     if ((Pos>>1) >= (LoopPos + Length))
         ~~~~~~~~~^~~~~~~~~~~~~~~~~~~~~
src/SPU.cpp:398:17: warning: comparison of integer expressions of different signedness: 's32' {aka 'int'} and 'u32' {aka 'unsigned int'} [-Wsign-compare]
         if (Pos == (LoopPos<<1))
             ~~~~^~~~~~~~~~~~~~~
src/SPU.cpp: In member function 'void SPU::CaptureUnit::Run(s32)':
src/SPU.cpp:561:21: warning: comparison of integer expressions of different signedness: 's32' {aka 'int'} and 'u32' {aka 'unsigned int'} [-Wsign-compare]
             if (Pos >= Length)
                 ~~~~^~~~~~~~~
src/SPU.cpp:584:21: warning: comparison of integer expressions of different signedness: 's32' {aka 'int'} and 'u32' {aka 'unsigned int'} [-Wsign-compare]
             if (Pos >= Length)
                 ~~~~^~~~~~~~~
src/GPU2DSoft.cpp: In member function 'void GPU2DSoft::DrawScanline_BGOBJ(u32)':
src/GPU2DSoft.cpp:27:62: warning: 'evb' may be used uninitialized in this function [-Wmaybe-uninitialized]
     u32 b = ((((val1 & 0x3F0000) * eva) + ((val2 & 0x3F0000) * evb)) >> 4) & 0x7F0000;
                                           ~~~~~~~~~~~~~~~~~~~^~~~~~
src/GPU2DSoft.cpp:86:14: note: 'evb' was declared here
     u32 eva, evb;
              ^~~
src/GPU2DSoft.cpp:27:34: warning: 'eva' may be used uninitialized in this function [-Wmaybe-uninitialized]
     u32 b = ((((val1 & 0x3F0000) * eva) + ((val2 & 0x3F0000) * evb)) >> 4) & 0x7F0000;
               ~~~~~~~~~~~~~~~~~~~^~~~~~
src/GPU2DSoft.cpp:86:9: note: 'eva' was declared here
     u32 eva, evb;
         ^~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/Wifi.o src/Wifi.cpp
src/Wifi.cpp: In function 'void Wifi::SendMPDefaultReply()':
src/Wifi.cpp:504:6: warning: unused variable 'txlen' [-Wunused-variable]
  int txlen = Platform::MP_SendPacket(reply, 12+28);
      ^~~~~
src/Wifi.cpp: In function 'void Wifi::SendMPAck()':
src/Wifi.cpp:534:6: warning: unused variable 'txlen' [-Wunused-variable]
  int txlen = Platform::MP_SendPacket(ack, 12+32);
      ^~~~~
src/Wifi.cpp: In function 'bool Wifi::ProcessTX(Wifi::TXSlot*, int)':
src/Wifi.cpp:659:17: warning: unused variable 'txlen' [-Wunused-variable]
             int txlen = Platform::MP_SendPacket(&RAM[slot->Addr], 12 + slot->Length);
                 ^~~~~
src/Wifi.cpp: In function 'void Wifi::USTimer(u32)':
src/Wifi.cpp:1097:31: warning: comparison of integer expressions of different signedness: 'u32' {aka 'unsigned int'} and 'int' [-Wsign-compare]
                 if (TXCurSlot == -1)
                     ~~~~~~~~~~^~~~~
src/Wifi.cpp: In function 'bool Wifi::CheckRX(bool)':
src/Wifi.cpp:898:44: warning: 'a_bss' may be used uninitialized in this function [-Wmaybe-uninitialized]
         bssidmatch = MACEqual(&RXBuffer[12 + a_bss], (u8*)&IOPORT(W_BSSID0));
                                         ~~~^~~~~~~
src/Wifi.cpp:900:36: warning: 'a_dst' may be used uninitialized in this function [-Wmaybe-uninitialized]
         if (!MACEqual(&RXBuffer[12 + a_dst], (u8*)&IOPORT(W_MACAddr0)) &&
                                 ~~~^~~~~~~
src/Wifi.cpp:846:13: warning: 'a_src' may be used uninitialized in this function [-Wmaybe-uninitialized]
         u32 a_src, a_dst, a_bss;
             ^~~~~
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/WifiAP.o src/WifiAP.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/config.o src/libretro/config.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/input.o src/libretro/input.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/libretro.o src/libretro/libretro.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/platform.o src/libretro/platform.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/screenlayout.o src/libretro/screenlayout.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/utils.o src/libretro/utils.cpp
src/libretro/platform.cpp: In function 'bool Platform::Mutex_TryLock(Platform::Mutex*)':
src/libretro/platform.cpp:156:4: warning: no return statement in function returning non-void [-Wreturn-type]
    }
    ^
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/GPU_OpenGL.o src/GPU_OpenGL.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/GPU3D_OpenGL.o src/GPU3D_OpenGL.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/OpenGLSupport.o src/OpenGLSupport.cpp
g++  -mcpu=cortex-a72 -mfpu=neon-fp-armv8 -O2 -O3 -fno-tree-vectorize  -std=gnu++14 -Wall -D__LIBRETRO__ -I./src/libretro/libretro-common/include -I./src/libretro -I./src  -DGIT_VERSION=\"" 7bbf8e1"\" -DHAVE_OPENGL -DOGLRENDERER_ENABLED -DCORE -DHAVE_THREADS   -c -osrc/libretro/opengl.o src/libretro/opengl.cpp
src/GPU3D_OpenGL.cpp: In function 'void GPU3D::GLRenderer::BuildPolygons(GPU3D::GLRenderer::RendererPolygon*, int)':
src/GPU3D_OpenGL.cpp:601:31: warning: comparison of integer expressions of different signedness: 'int' and 'u32' {aka 'unsigned int'} [-Wsign-compare]
             for (int j = 0; j < poly->NumVertices; j++)
                             ~~^~~~~~~~~~~~~~~~~~~
src/GPU3D_OpenGL.cpp:607:31: warning: comparison of integer expressions of different signedness: 'u32' {aka 'unsigned int'} and 's32' {aka 'int'} [-Wsign-compare]
                     if (lastx == vtx->FinalPosition[0] &&
                         ~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~
src/GPU3D_OpenGL.cpp:608:31: warning: comparison of integer expressions of different signedness: 'u32' {aka 'unsigned int'} and 's32' {aka 'int'} [-Wsign-compare]
                         lasty == vtx->FinalPosition[1]) continue;
                         ~~~~~~^~~~~~~~~~~~~~~~~~~~~~~~
src/GPU3D_OpenGL.cpp:650:35: warning: comparison of integer expressions of different signedness: 'int' and 'u32' {aka 'unsigned int'} [-Wsign-compare]
                 for (int j = 0; j < poly->NumVertices; j++)
                                 ~~^~~~~~~~~~~~~~~~~~~
src/GPU3D_OpenGL.cpp:681:35: warning: comparison of integer expressions of different signedness: 'int' and 'u32' {aka 'unsigned int'} [-Wsign-compare]
                 for (int j = 0; j < poly->NumVertices; j++)
                                 ~~^~~~~~~~~~~~~~~~~~~
src/GPU3D_OpenGL.cpp:744:35: warning: comparison of integer expressions of different signedness: 'int' and 'u32' {aka 'unsigned int'} [-Wsign-compare]
                 for (int j = 0; j < poly->NumVertices; j++)
                                 ~~^~~~~~~~~~~~~~~~~~~
src/GPU3D_OpenGL.cpp:773:27: warning: comparison of integer expressions of different signedness: 'int' and 'u32' {aka 'unsigned int'} [-Wsign-compare]
         for (int j = 1; j < poly->NumVertices; j++)
                         ~~^~~~~~~~~~~~~~~~~~~
src/GPU3D_OpenGL.cpp: In function 'void GPU3D::GLRenderer::RenderFrame()':
src/GPU3D_OpenGL.cpp:1315:27: warning: comparison of integer expressions of different signedness: 'int' and 'u32' {aka 'unsigned int'} [-Wsign-compare]
         for (int i = 0; i < RenderNumPolygons; i++)
                         ~~^~~~~~~~~~~~~~~~~~~
src/GPU3D_OpenGL.cpp:1259:24: warning: 'vram' may be used uninitialized in this function [-Wmaybe-uninitialized]
         glTexSubImage2D(GL_TEXTURE_2D, 0, 0, i*8, 1024, 8, GL_RGBA, GL_UNSIGNED_SHORT_1_5_5_5_REV, vram);
src/GPU3D_OpenGL.cpp:1244:24: warning: 'vram' may be used uninitialized in this function [-Wmaybe-uninitialized]
         glTexSubImage2D(GL_TEXTURE_2D, 0, 0, i*128, 1024, 128, GL_RED_INTEGER, GL_UNSIGNED_BYTE, vram);
g++  -shared -static-libgcc -static-libstdc++ -s -Wl,--version-script=./src/libretro/link.T -Wl,--no-undefined  -omelonds_libretro.dll ./src/xxhash/xxhash.o ./src/tiny-AES-c/aes.o ./src/libretro/libretro-common/compat/compat_strl.o ./src/libretro/libretro-common/compat/fopen_utf8.o ./src/libretro/libretro-common/compat/compat_posix_string.o ./src/libretro/libretro-common/compat/compat_strcasestr.o ./src/libretro/libretro-common/encodings/encoding_utf.o ./src/libretro/libretro-common/file/file_path.o ./src/libretro/libretro-common/streams/file_stream.o ./src/libretro/libretro-common/streams/file_stream_transforms.o ./src/libretro/libretro-common/streams/memory_stream.o ./src/libretro/libretro-common/string/stdstring.o ./src/libretro/libretro-common/vfs/vfs_implementation.o ./src/libretro/libretro-common/glsm/glsm.o ./src/libretro/libretro-common/glsym/rglgen.o ./src/libretro/libretro-common/glsym/glsym_gl.o ./src/libretro/libretro-common/rthreads/rthreads.o ./src/libretro/libretro-common/rthreads/rsemaphore.o ./src/NDS.o ./src/AREngine.o ./src/ARM.o ./src/ARMInterpreter.o ./src/ARMInterpreter_ALU.o ./src/ARMInterpreter_Branch.o ./src/ARMInterpreter_LoadStore.o ./src/CP15.o ./src/CRC32.o ./src/DMA.o ./src/DSi.o ./src/DSi_AES.o ./src/DSi_Camera.o ./src/DSi_I2C.o ./src/DSi_NDMA.o ./src/DSi_NWifi.o ./src/DSi_SD.o ./src/DSi_SPI_TSC.o ./src/DSiCrypto.o ./src/GBACart.o ./src/GPU.o ./src/GPU2D.o ./src/GPU2DSoft.o ./src/GPU3D.o ./src/GPU3D_Soft.o ./src/NDSCart.o ./src/RTC.o ./src/Savestate.o ./src/SPI.o ./src/SPU.o ./src/Wifi.o ./src/WifiAP.o ./src/libretro/config.o ./src/libretro/input.o ./src/libretro/libretro.o ./src/libretro/platform.o ./src/libretro/screenlayout.o ./src/libretro/utils.o ./src/GPU_OpenGL.o ./src/GPU3D_OpenGL.o ./src/OpenGLSupport.o ./src/libretro/opengl.o  -lws2_32 -lwinmm -lopengl32 -lm
/usr/bin/ld: cannot find -lws2_32
/usr/bin/ld: cannot find -lwinmm
/usr/bin/ld: cannot find -lopengl32
collect2: error: ld returned 1 exit status
make: *** [Makefile:424: melonds_libretro.dll] Error 1
/home/pi
/home/pi/RetroPie-Setup/tmp/build/lr-melonDS /home/pi

= = = = = = = = = = = = = = = = = = = = =
Installing 'lr-melonDS' : NDS/DSI emu requries bios and firmware from DS/DSI port for libretro
= = = = = = = = = = = = = = = = = = = = =

/home/pi
Could not successfully install NDS/DSI emu requries bios and firmware from DS/DSI port for libretro (/home/pi/RetroPie-Setup/tmp/build/lr-melonDS/lr-melonDS/src/libretro/libretro.o not found).

Log ended at: Thu Dec 31 09:49:10 EST 2020
Total running time: 0 hours, 0 mins, 39 secs
