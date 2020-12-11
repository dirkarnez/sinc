sinc
====
### TODO
- FLTK for confirmation
- .gitignore-like mechanisem
- play around with C++20
  - Modules
  - Coroutines

### Robocopy
sync.bat
```
robocopy . C:\Users\Administrator\Downloads\Target\ /E /Z /ZB /R:5 /W:5 /TBD /V /XD "db" ".git" "src/*" /XF "secret.cmd" "sync.bat"
```
