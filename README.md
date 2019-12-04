# WebServer
## You can access 127.0.0.1 with your own files.


* Usage:

Create a BAT file and enter:

> @echo off
> "WebDev.WebServer.EXE" (/port:%port%) /path:"%path%" /vpath:"%webpath"

Example1:

> @echo off
> "WebDev.WebServer.EXE" /path:"D:\test" /vpath:"/test

** Then open a new tab and enter "127.0.0.1/test" or "localhost/test"


Example2:

> @echo off
> "WebDev.WebServer.EXE" port:8088 /path:"D:\test" /vpath:"/test

** Then open a new tab and enter "127.0.0.1:8088/test"
