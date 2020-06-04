@echo off
set "path=server.jar"
set "mapPath=server.txt"
set "output=deobf-server.jar"
set "fixlocalvar=delete"
call ../../MC-Remapper.bat "%path%" "%mapPath%" "--output=%output%" "--fixlocalvar=%fixlocalvar%"