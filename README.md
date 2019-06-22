# Kali-Setup

# Fully automated bash script to setup your Kali system, Tested on Kali 2017.1 Vmware x64.

This idea came to me while taking the OSCP.  I took my own initiative to create this script, though it's far from perfect,I created this script as part of continuing my education, as a result I applied several different methodologies in creating it.

I borrowed several lines from g0tmi1ks script though most of the lines are available open source on the net.


Some of the repos are included in the full Kali Distro, I also added additional software in order to fix several known issues with Kali


Express Install: It will install basic apps and configure services and your system for daily use.

	Atom  	   	Asciinema	Pure-FTPd	Chromium 	Hexchat   	Shutter
	Apache2		Tilda		Terminator 	htop 		Mysql		Conky 		
	Dropbox 	psmisc 		SSH		Icedove   	Pipe Vievwer 	Tft
	LibreOffice     Filezilla    	Gitkraken	lnav


Full Install: It will Install Express module apps, full package repos and let your system ready for Pentesting.

	MSF			OpenVas			Sshuttle	GCC		MITMf 		Wig
	GoBuster		Armitage		VFeed 		Pfi 		MinGW 		Wordlists
	CMSmap 			reGeorg 		Python		Graudit 	AccessChk	Wine
	Smbspider		Droopescan		Patetor		Pycharm		Daemonfs 	PsExec.exe
	Hyperion 		CrackMapExec		Crowbar	 	Clusterd 	wdiff		Proxychains
	Veil-framework		BDFProxy		Credcrack	Subterfuge 	Webhandler 	Vbindiff
	HttpTunnel		OP-Packers 		BetterCap	Empire		Azazel		Gnmap-Parser
	Fuzzbunch		Gophish



Just do:

# git clone https://github.com/kawaxi/kali-setup.git

For help do:

# Start -h



Pending Ideas:
* Working with counters inside modules
* Need to Include personalized exploits to exploit DB.
* Set key macros for programming.  
* Make script to trap TERM signal.



# Change Log


June 2019
* Waterfox has been added for legacy addons support as alternative to firefox-esr


Augoust

* Installed Requirements for droopscan.


June Update
* New addon added to firefox-esr , now there are 20 installed.
* Bin file Created for Burpsuite-Pro
* Fixed and ported to gtk3 terminator's plugin to capture all console output with timestamp for pentesting.
* Few tweaks added for Hyperion.


-- 2017 --

November Update
* New Extentions added to firefox-esr (hack the form, NoRedirect, PassiveRecon, Wappalyzer, H3LL4R_H5H HackMod for HackBar)
* New shells added from https://webshell.co/
* JSWebMeter shell added.
* Fixed some small errors.
* Gophish Fishing Toolkit added.

October Update
* Fixed tilda config file problem.
* Fixed problem with bash aliases made by a typo.
* Updated some github repos.
* Made some code improvements.
* Made optimizations to make code fully compatible with Kali 2017.2 & 2016.2
* Fixed Problem with Hyperion
* New Extentions added to firefox-esr


June 16th
* Unified incoming conections into access.log for Apache2
*	Fixed little misconfiguration in Tilda
* Eternalblue-Doublepulsar Metasploit module Added.
* Fuzzbunch Alias Created.
* Imsonia Webshell Added.
* Shellter AV Evasion & shellcode injection added to full install module..

May 2nd
* Fuzzbunch install added.

April 27th
* Some tweaks made for Kali 2017.1
* Removed fix for vmtools since is not longer needed.
* We cleaned code to install caffeine extension
* Fixed some colors for warnings and notices


April 26th
* common List link added to root folder
* Chromium added to Kali
* Changed method for Dropbox installation & Added to Startup
* OTR plug-in  enabled on Hexchat
* Hold on openssh-server & bash-completion to avoid configuration issues.
* Some IF conditions added to save time.
* Fixed Issue when installing Caffeine Extension.
* Added Time sync for stats during installation.
* Dropbox added to Express Install module.
* General code cleaning.

March 8th
* Config file for Tilda created and applied personal Configuration.
* Changed filter for installing MingW and GCC libs.

March 4th
* Fixed time sync problem by adding another safety layer by changging daemon behavior.
* Added Sublime text as an option for the 32 bits version
* Enabled favorites for gnome dash to dock for 32 bits OS.
* Condition added to check for MingW Libs in order to save time when Installing.
* Condition added to check for Wine in order to save time.
* Condition added to skip installed for Veil-Evasion.

Feb 25th
* Fixed time sync problem
* Worked on comment standard
* Add msf alias for Msfconsole
* Cleaning Module Created.
* Moved Colors definition to Visual Module.
* Added Tilda to express Installation Module.

Feb 22nd
* Copied Windows-binaries to FTP, TFTP, and Apache services folder.

Feb 20th
* Fixed Little Issue with IRC peventsfile.

Feb 19th 2017
* Fixed problem with  gsettings and Dash to Dock
* Fixed linked for pshtoolkit
* Added Bookmarks for nautilus
* Added Wallpapers
* Random Wallpapers for Gnome enabled

Feb 1st 2017
* Fixed Commenting format in Start File.
* Fixed Several minor issues.
