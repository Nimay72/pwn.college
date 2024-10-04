```Connected!
hacker@commands~an-epic-filesystem-quest:~$ pwd
/home/hacker
hacker@commands~an-epic-filesystem-quest:~$ cd ../..
hacker@commands~an-epic-filesystem-quest:/$ ls -a
.   .dockerenv  bin   challenge  etc   home  lib32  libx32  mnt  opt   root  sbin  sys  usr
..  LEAD        boot  dev        flag  lib   lib64  media   nix  proc  run   srv   tmp  var
hacker@commands~an-epic-filesystem-quest:/$ cat LEAD
Lucky listing!
The next clue is in: /opt/aflplusplus/nyx_mode/QEMU-Nyx/tests/tcg/openrisc

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/$ cd /opt/aflplusplus/nyx_mode/QEMU-Nyx/tests/tcg/openrisc
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/QEMU-Nyx/tests/tcg/openrisc$ ls -a
.            test_addic.c   test_fx.c      test_lf_gts.c  test_logic.c  test_sfeqi.c   test_sfgtu.c   test_sfltsi.c
..           test_and_or.c  test_j.c       test_lf_les.c  test_lx.c     test_sfges.c   test_sfgtui.c  test_sfltu.c
.MESSAGE     test_bf.c      test_jal.c     test_lf_lts.c  test_movhi.c  test_sfgesi.c  test_sfles.c   test_sfltui.c
Makefile     test_bnf.c     test_lf_add.c  test_lf_mul.c  test_mul.c    test_sfgeu.c   test_sflesi.c  test_sfne.c
test_add.c   test_div.c     test_lf_div.c  test_lf_nes.c  test_muli.c   test_sfgeui.c  test_sfleu.c   test_sfnei.c
test_addc.c  test_divu.c    test_lf_eqs.c  test_lf_rem.c  test_mulu.c   test_sfgts.c   test_sfleui.c  test_sub.c
test_addi.c  test_extx.c    test_lf_ges.c  test_lf_sub.c  test_sfeq.c   test_sfgtsi.c  test_sflts.c
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/QEMU-Nyx/tests/tcg/openrisc$ cat ..
cat: ..: Is a directory
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/QEMU-Nyx/tests/tcg/openrisc$ /..
ssh-entrypoint: /..: Is a directory
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/QEMU-Nyx/tests/tcg/openrisc$ cat .MESSAGE
Lucky listing!
The next clue is in: /usr/lib/modules-load.d

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/QEMU-Nyx/tests/tcg/openrisc$ /usr/lib/modules-load.d
ssh-entrypoint: /usr/lib/modules-load.d: Is a directory
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/QEMU-Nyx/tests/tcg/openrisc$ ls /usr/lib/modules-load.d
SPOILER-TRAPPED
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/QEMU-Nyx/tests/tcg/openrisc$ cat /usr/lib/modules-load.d/SPOILER-TRAPPED
Lucky listing!
The next clue is in: /opt/linux/linux-5.4/include/config/old
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/QEMU-Nyx/tests/tcg/openrisc$ ls  /opt/linux/linux-5.4/include/config/old
SNIPPET  sigsuspend3.h
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/QEMU-Nyx/tests/tcg/openrisc$ cat  /opt/linux/linux-5.4/include/config/old/SNIPPET
Congratulations, you found the clue!
The next clue is in: /usr/local/lib/python3.8/dist-packages/pwnlib/shellcraft/templates/arm/freebsd
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/QEMU-Nyx/tests/tcg/openrisc$ cat //usr/local/lib/python3.8/dist-packages/pwnlib/shellcraft/templates/arm/freebsd
cat: //usr/local/lib/python3.8/dist-packages/pwnlib/shellcraft/templates/arm/freebsd: Is a directory
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/QEMU-Nyx/tests/tcg/openrisc$ cat /usr/local/lib/python3.8/dist-packages/pwnlib/shellcraft/templates/arm/freebsd
cat: /usr/local/lib/python3.8/dist-packages/pwnlib/shellcraft/templates/arm/freebsd: Is a directory
hacker@commands~an-epic-filesystem-quest:/opt/aflplusplus/nyx_mode/QEMU-Nyx/tests/tcg/openrisc$ cd /usr/local/lib/python3.8/dist-packages/pwnlib/shellcraft/templates/arm/freebsd
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/pwnlib/shellcraft/templates/arm/freebsd$ ls -a
.  ..  SECRET  __doc__  syscall.asm
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/pwnlib/shellcraft/templates/arm/freebsd$ cat SECRET
Great sleuthing!
The next clue is in: /usr/lib/python3/dist-packages/packaging-20.3.egg-info

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/pwnlib/shellcraft/templates/arm/freebsd$ cat /usr/lib/python3/dist-packages/packaging-20.3.egg-info
cat: /usr/lib/python3/dist-packages/packaging-20.3.egg-info: Is a directory
hacker@commands~an-epic-filesystem-quest:/usr/local/lib/python3.8/dist-packages/pwnlib/shellcraft/templates/arm/freebsd$ cd /usr/lib/python3/dist-packages/packaging-20.3.egg-info
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/packaging-20.3.egg-info$ ls -a
.  ..  .BLUEPRINT  PKG-INFO  dependency_links.txt  requires.txt  top_level.txt
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/packaging-20.3.egg-info$ cat  .BLUEPRINT
Great sleuthing!
The next clue is in: /usr/share/doc/xxd

Watch out! The next clue is **trapped**. You'll need to read it out without 'cd'ing into the directory; otherwise, the clue will self destruct!
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/packaging-20.3.egg-info$ cat /usr/share/doc/xxd
cat: /usr/share/doc/xxd: Is a directory
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/packaging-20.3.egg-info$ ls /usr/share/doc/xxd
CLUE-TRAPPED  NEWS.Debian.gz  changelog.Debian.gz  copyright
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/packaging-20.3.egg-info$ cat CLUE-TRAPPED
cat: CLUE-TRAPPED: No such file or directory
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/packaging-20.3.egg-info$ cat  /usr/share/doc/xxd/CLUE-TRAPPED
Lucky listing!
The next clue is in: /opt/linux/linux-5.4/drivers/gpu/drm/nouveau/nvkm/engine/mpeg

The next clue is **hidden** --- its filename starts with a '.' character. You'll need to look for it using special options to 'ls'.
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/packaging-20.3.egg-info$ cat  /opt/linux/linux-5.4/drivers/gpu/drm/nouveau/nvkm/engine/mpeg
cat: /opt/linux/linux-5.4/drivers/gpu/drm/nouveau/nvkm/engine/mpeg: Is a directory
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/packaging-20.3.egg-info$ ls  /opt/linux/linux-5.4/drivers/gpu/drm/nouveau/nvkm/engine/mpeg
Kbuild  g84.c  nv31.c  nv31.h  nv40.c  nv44.c  nv50.c  priv.h
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/packaging-20.3.egg-info$ ls -a  /opt/linux/linux-5.4/drivers/gpu/drm/nouveau/nvkm/engine/mpeg
.  ..  .REVELATION  Kbuild  g84.c  nv31.c  nv31.h  nv40.c  nv44.c  nv50.c  priv.h
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/packaging-20.3.egg-info$ cat  /opt/linux/linux-5.4/drivers/gpu/drm/nouveau/nvkm/engine/mpeg/.REVELATION
Great sleuthing!
The next clue is in: /usr/share/perl/5.30.0/Text

The next clue is **delayed** --- it will not become readable until you enter the directory with 'cd'.
hacker@commands~an-epic-filesystem-quest:/usr/lib/python3/dist-packages/packaging-20.3.egg-info$ cd /usr/share/perl/5.30.0/Text
hacker@commands~an-epic-filesystem-quest:/usr/share/perl/5.30.0/Text$ ls -a
.  ..  Abbrev.pm  Balanced.pm  ParseWords.pm  TEASER  Tabs.pm  Wrap.pm
hacker@commands~an-epic-filesystem-quest:/usr/share/perl/5.30.0/Text$ cat TEASER
CONGRATULATIONS! Your perserverence has paid off, and you have found the flag!
It is: pwn.college{oNxYc7W6tPCr75ceQf9f2lXdxFi.dljM4QDL1EjN0czW}
```
