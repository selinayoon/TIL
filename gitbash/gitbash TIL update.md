### 깃배쉬로 TIL 업뎃

```gitbach
student@DESKTOP MINGW64 ~
$ pwd
/c/Users/student

student@DESKTOP MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Application Data'@
 change/
 Contacts/
 Cookies@
 Desktop/
 Documents/
 Downloads/
 Favorites/
 Intel/
 Links/
'Local Settings'@
 MicrosoftEdgeBackups/
 Music/
'My Documents'@
 NetHood@
 NTUSER.DAT
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 NTUSER.DAT{9345b422-eef0-11e8-9bfa-98838987b765}.TM.blf
 NTUSER.DAT{9345b422-eef0-11e8-9bfa-98838987b765}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{9345b422-eef0-11e8-9bfa-98838987b765}.TMContainer00000000000000000002.regtrans-ms
 NTUSER.DAT{9b83b4f9-ebbf-11e8-9bf0-9883898797b5}.TM.blf
 NTUSER.DAT{9b83b4f9-ebbf-11e8-9bf0-9883898797b5}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{9b83b4f9-ebbf-11e8-9bf0-9883898797b5}.TMContainer00000000000000000002.regtrans-ms
 NTUSER.DAT{b264deb3-eb9c-11e8-9bef-9883898797b5}.TM.blf
 NTUSER.DAT{b264deb3-eb9c-11e8-9bef-9883898797b5}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{b264deb3-eb9c-11e8-9bef-9883898797b5}.TMContainer00000000000000000002.regtrans-ms
 NTUSER.DAT{bbd90b96-e875-11e8-b39d-988389879652}.TM.blf
 NTUSER.DAT{bbd90b96-e875-11e8-b39d-988389879652}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{bbd90b96-e875-11e8-b39d-988389879652}.TMContainer00000000000000000002.regtrans-ms
 ntuser.ini
 OneDrive/
 Pictures/
 PrintHood@
 Recent@
'Saved Games'/
 Searches/
 SendTo@
 startbootstrap-resume-gh-pages/
 Templates@
 TIL-eunsol/
 Videos/
'시작 메뉴'@

student@DESKTOP MINGW64 ~
$ cd TIL-eunsol/

student@DESKTOP MINGW64 ~/TIL-eunsol (master)
$ cd add .

student@DESKTOP MINGW64 ~/TIL-eunsol (master)
$ git commit -m "D01 | 190102 | startcamp"

student@DESKTOP MINGW64 ~/TIL-eunsol (master)
$ git push

```

깃허브에서 확인



### 에러 발생시 

깃허브에서 파일을 만들거나 수정하면 에러가 뜬다 Create new file 사용시

```gitbash
student@DESKTOP MINGW64 ~
$ pwd
/c/Users/student

student@DESKTOP MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Application Data'@
 change/
 Contacts/
 Cookies@
 Desktop/
 Documents/
 Downloads/
 Favorites/
 Intel/
 Links/
'Local Settings'@
 MicrosoftEdgeBackups/
 Music/
'My Documents'@
 NetHood@
 NTUSER.DAT
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 NTUSER.DAT{9345b422-eef0-11e8-9bfa-98838987b765}.TM.blf
 NTUSER.DAT{9345b422-eef0-11e8-9bfa-98838987b765}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{9345b422-eef0-11e8-9bfa-98838987b765}.TMContainer00000000000000000002.regtrans-ms
 NTUSER.DAT{9b83b4f9-ebbf-11e8-9bf0-9883898797b5}.TM.blf
 NTUSER.DAT{9b83b4f9-ebbf-11e8-9bf0-9883898797b5}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{9b83b4f9-ebbf-11e8-9bf0-9883898797b5}.TMContainer00000000000000000002.regtrans-ms
 NTUSER.DAT{b264deb3-eb9c-11e8-9bef-9883898797b5}.TM.blf
 NTUSER.DAT{b264deb3-eb9c-11e8-9bef-9883898797b5}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{b264deb3-eb9c-11e8-9bef-9883898797b5}.TMContainer00000000000000000002.regtrans-ms
 NTUSER.DAT{bbd90b96-e875-11e8-b39d-988389879652}.TM.blf
 NTUSER.DAT{bbd90b96-e875-11e8-b39d-988389879652}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{bbd90b96-e875-11e8-b39d-988389879652}.TMContainer00000000000000000002.regtrans-ms
 ntuser.ini
 OneDrive/
 Pictures/
 PrintHood@
 Recent@
'Saved Games'/
 Searches/
 SendTo@
 startbootstrap-resume-gh-pages/
 Templates@
 TIL-eunsol/
 Videos/
'시작 메뉴'@

student@DESKTOP MINGW64 ~
$ cd TIL-eunsol/

student@DESKTOP MINGW64 ~/TIL-eunsol (master)
$ git pull\
>
remote: Enumerating objects: 13, done.
remote: Counting objects: 100% (13/13), done.
remote: Compressing objects: 100% (11/11), done.
remote: Total 12 (delta 2), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (12/12), done.
From https://github.com/selinayoon/TIL
   f3f2016..91dc5ad  master     -> origin/master
Already up to date!
Merge made by the 'recursive' strategy.

student@DESKTOP MINGW64 ~/TIL-eunsol (master)
$ git push
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 12 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 624 bytes | 624.00 KiB/s, done.
Total 5 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/selinayoon/TIL.git
   91dc5ad..3cae158  master -> master

student@DESKTOP MINGW64 ~/TIL-eunsol (master)
$

```

로 진행하기

### 