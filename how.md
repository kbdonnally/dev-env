# Tools:

1. Sublime Text 3
2. Git
3. Ruby Windows Installer
4. Uru
5. 7-Zip
6. Sass
7. Node.js & npm
8. Omeka
9. AMPPS
10. Python 3
11. Associated PATH edits
12. Other: Atom, ...

# How:

### 1. Sublime Text 3:

* Site: [download page](https://www.sublimetext.com/3)

* Executable: [build 3143](https://download.sublimetext.com/Sublime%20Text%20Build%203143%20x64%20Setup.exe)

* **Configuration:**
	* For your theme and color scheme preference...
	* Go to 'Tools -> Command Palette'
	* It'll come up w/ an input bar: start typing "Install Package Control"
	* Then, use Package Control to install the "predawn" theme
	* This'll make the tabs all weirdy, which you don't super dig, so:
	* Use "Adaptive" as the *theme* setting, and "predawn" for *color scheme*
	* To set Markdown stuff: with a .md file open...
		* Under "Preferences" -> "Syntax-Specific" -> paste in the following: ```"color_scheme": "Packages/Predawn/predawn-markdown.tmTheme"```

### 2. Git:

* Link: auto-downloads [on load](https://git-scm.com/download/win)

* Installs Git, Bash, and adds Git to CMD (set-up wizard options)

* **Configuration**:
	- Settings as they now stand:

	```user.name=<name>
	user.email=<email>
	alias.br=branch
	alias.co=checkout
	alias.ci=commit
	alias.lg=log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit```

	- Commands to do so:

	1. ```git config --global <name/email> "name/email"```
	2. ```git config --global alias.<new command> <what it's an alias for>```

	-NB: if there's a space in the thing you want to alias, must wrap in "double quotes". E.g.:

	```git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"```

	-To see lines that changed with newly configured git log command, add option ```-p```. [Source](https://coderwall.com/p/euwpig/a-better-git-log) for "lg" instructions.

	**NB: Write down your actual git log configuration here! Is on other computer rn, ironically**

### 3. Ruby:

* Ruby Installer for Windows: [downloads archive](https://rubyinstaller.org/downloads/archives/). Pick desired version.

	-NB: if need more than one version of Ruby, just literally do this process again with a different version number. It won't install anything redundant.

* Executable: [version 2.4.1](https://github.com/oneclick/rubyinstaller2/releases/download/2.4.1-1/rubyinstaller-2.4.1-1-x64.exe)

* Ruby Installer 2.4.1-1 also installs MSYS2 toolkit. (Anything above 2.4.0 does.)

* **Installer initial options: enter '1 2 3'**

### 4. Uru:

* Like Ruby Version Manager (RVM), but works for Windows and is a lot more lightweight.

* Link: [downloads page](https://bitbucket.org/jonforums/uru/wiki/Downloads)

* Executable: [Windows version](https://bitbucket.org/jonforums/uru/downloads/uru-0.8.4-windows-x86.7z)

* This [article](https://www.neverletdown.net/2015/08/managing-multiple-ruby-versions-with-uru.html) is a hell of an explainer on how to use Uru effectively, including command line instructions.

*NB: download must be unzipped with 7-Zip.*

### 5. 7-Zip

* Executable: [version 16.04](http://www.7-zip.org/a/7z1604-x64.exe)

* Main [download page](http://www.7-zip.org/download.html) in case January 2018 beta release is no longer beta by next computer Sad Day

### 6. Sass:

* Use ```gem install sass``` in the directory where you'll be tracking a given project's SCSS/CSS files.

* *Make Sublime recognize SCSS syntax:* search Packages for "Sass", or follow the instructions in [this link](https://packagecontrol.io/packages/Sass).

### 7. Node.js/npm

* Link: [download page](https://nodejs.org/en/)

* Executable: [version 8.9.4](https://nodejs.org/dist/v8.9.4/node-v8.9.4-x64.msi)

### 8. Omeka

### 9. AMPPS

### 10. Python 3
**Hi this is where you stopped on 1/22/18 finish up deets for your future self pls <3**

### 11. PATH:

* Environment variables:

	```C:\Users\%USERNAME%\Desktop\tools\Ruby24-x64\bin```
	```%USERPROFILE%\AppData\Local\Microsoft\WindowsApps``` <-- unsure if needed
	```C:\Users\%USERNAME%\AppData\Local\Programs\Git\cmd```
	```C:\Users\%USERNAME%\AppData\Roaming\npm```

* Extensions:

	```%PATHEXT%;.RB;.RBW```