# Hacky Dev Env:

## So you [deleted/broke/lost/don't have access to] your computer.

But you do have a different computer! It just... doesn't have any of your stuff on it. Let's try to make restoring a workable development environment as quick/painless as possible. *NB: These instructions are for Windows 10, should some poor soul besides myself happen upon this repo.*

As much of the stuff you need is included here as possible; if not, there'll hopefully be specific instructions and links. (Also, if the stuff is like, hella out of date you should re-download it. This is all from January 2018.)

## Tools:

1. Text editor (Sublime Text 3)
2. Ruby Windows Installer
3. Uru
4. Ruby (v2.4.1 for SLab site, as of January 2018) -> link to site repo
5. Git (Bash)
6. Sass
7. Node.js & npm
8. Python 3
9. 7-Zip
10. Associated PATH edits

## How:

10. PATH:

	* Environment variables:

	```C:\Users\%USERNAME%\Desktop\tools\Ruby24-x64\bin```
	```%USERPROFILE%\AppData\Local\Microsoft\WindowsApps``` <-- unsure if needed
	```C:\Users\%USERNAME%\AppData\Local\Programs\Git\cmd```
	```C:\Users\%USERNAME%\AppData\Roaming\npm```

	* Extensions:

	```%PATHEXT%;.RB;.RBW```