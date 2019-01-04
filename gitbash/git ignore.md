https://github.com/github/gitignore/blob/master/Python.gitignore

 깃 이그노어 설정  - 특정한 파일 git add . 할 때  파일 올리지 않기 위해 

저기서 코드 긁어오기

```python
# Byte-compiled / optimized / DLL files
__pycache__/
*.py[cod]
*$py.class

# C extensions
*.so

# Distribution / packaging
.Python
build/
develop-eggs/
dist/
downloads/
eggs/
.eggs/
lib/
lib64/
parts/
sdist/
var/
wheels/
share/python-wheels/
*.egg-info/
.installed.cfg
*.egg
MANIFEST

# PyInstaller
#  Usually these files are written by a python script from a template
#  before PyInstaller builds the exe, so as to inject date/other infos into it.
*.manifest
*.spec

# Installer logs
pip-log.txt
pip-delete-this-directory.txt

# Unit test / coverage reports
htmlcov/
.tox/
.nox/
.coverage
.coverage.*
.cache
nosetests.xml
coverage.xml
*.cover
.hypothesis/
.pytest_cache/

# Translations
*.mo
*.pot

# Django stuff:
*.log
local_settings.py
db.sqlite3

# Flask stuff:
instance/
.webassets-cache

# Scrapy stuff:
.scrapy

# Sphinx documentation
docs/_build/

# PyBuilder
target/

# Jupyter Notebook
.ipynb_checkpoints

# IPython
profile_default/
ipython_config.py

# pyenv
.python-version

# celery beat schedule file
celerybeat-schedule

# SageMath parsed files
*.sage.py

# Environments
.env
.venv
env/
venv/
ENV/
env.bak/
venv.bak/

# Spyder project settings
.spyderproject
.spyproject

# Rope project settings
.ropeproject

# mkdocs documentation
/site

# mypy
.mypy_cache/
.dmypy.json
dmypy.json

# Pyre type checker
.pyre/
```

git bash 열기

```
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
$ touch .gitignore

student@DESKTOP MINGW64 ~/TIL-eunsol (master)
$ ls -a
./  ../  .git/  .gitignore  flask/  gitbash/  html/  python/

student@DESKTOP MINGW64 ~/TIL-eunsol (master)
$ code .

```

하면 vs코드 열리고

.gitignore 파일에 아까 그 코드 붙여넣고 저장



```
student@DESKTOP MINGW64 ~/TIL-eunsol (master)
$ git add .

student@DESKTOP MINGW64 ~/TIL-eunsol (master)
$ git commit -m "D01 | 190102 | gitignore 설정"
[master 94409fb] D01 | 190102 | gitignore 설정
 2 files changed, 281 insertions(+)
 create mode 100644 .gitignore
 create mode 100644 gitbash/gitbash TIL update.md

student@DESKTOP MINGW64 ~/TIL-eunsol (master)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 2.22 KiB | 2.22 MiB/s, done.
Total 5 (delta 0), reused 0 (delta 0)
To https://github.com/selinayoon/TIL.git
   3cae158..94409fb  master -> master

```



