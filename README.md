sinc
====
### TODO
- Elements for confirmation
  - display what chosen as radio-button group
- .gitignore-like mechanisem
- play around with C++20
  - Modules
  - Coroutines

### Robocopy
sync.bat
```
robocopy . C:\Users\Administrator\Downloads\Target\ /E /Z /ZB /R:5 /W:5 /TBD /V /XD "db" ".git" "src/*" /XF "secret.cmd" "sync.bat"
```

### Reference
- [puppetSpace/Replicate: Application that sync files, just to try out dotnet core](https://github.com/puppetSpace/Replicate)
- [OctopusDeploy/Octodiff: 100% C# implementation of remote delta compression based on the rsync algorithm](https://github.com/OctopusDeploy/Octodiff)
- [The rsync algorithm](https://rsync.samba.org/tech_report/tech_report.html)
