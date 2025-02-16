![Product cover](https://raw.githubusercontent.com/Smu1zel/SharperImageKeychainWin11/refs/heads/master/res/screenshot.jpg)

# Intro
If you've tried to use the software for these products on any remotely modern version of Windows, you've probably ran into this.
![This comes up even if it's plugged in](https://raw.githubusercontent.com/Smu1zel/SharperImageKeychainWin11/refs/heads/master/res/cover.jpg)

Despite playing around with compatibility settings, nothing works. What could the issue be?

# The problem, and a solution
Turns out, the software doesn't seem to work on anything newer than XP, *except* one version, a revision of 2.5 that seems to have only been released on [MerchSource's website](https://web.archive.org/web/20120106024849if_/http://mscustomercare.com/#:~:text=Digital%20Photo%20Keychain) intended to fix Windows Vista support. Getting this to work on modern versions of Windows is much simpler.

# Steps
1. Download the ZIP from [here](https://github.com/Smu1zel/SharperImageKeychainWin11/raw/refs/heads/master/2.5b%20%2898-11%29/Digital%20Photo%20Keychain%20Software.zip).
2. Run the included setup.
3. Follow the onscreen prompts.
4. Once the program has been installed, navigate to where you installed the program. on 64-bit systems, this will be ``C:\Program Files (x86)\Photo Viewer``, and on 32-bit systems, this will be ``C:\Program Files\Photo Viewer``.
5. Right click the executable.
6. Click Properties.
7. Click the Compatibility tab.
8. Set up as shown:
	Compatibility mode: Windows Vista  
	[✓] Run this program as an administrator.
9. Click OK.
10. Plug in your keychain and start the program. Everything should just work. Enjoy. 