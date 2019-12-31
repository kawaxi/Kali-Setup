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
add infoga
add sniper




# Change Log


June 2019
* Waterfox has been added for legacy addons support as alternative to firefox-esr.
* Improved Terminator Logger plugging KawaxisLogger to make it work with updated systems.
* Testssl SSL audit script added.
