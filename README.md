
**The Command Line**


** customise your command line**

 There are the original command-line tools, and there are many graphical user interfaces of varying capabilities. 
 Also you can create youe own command line.
 
 customise your command line to make it pretty and useful (ie. git branch/branch status parser)
to modify or build according to individual or personal specifications orpreference:
to customize an automobile.


**Install using a package manager**


**Ubuntu** is based on **Debian** and all software packages are **.deb** files.
Most software packages are free available from Ubuntu Repositories.


Adding and removing software and System Update are critical procedures, as for every system.
Debian packages (and Ubuntu of course) can be managed from command line using the package manager “apt & dpkg”.


**What are Repositories?**


programs are stored in software archives commonly referred to as repositories.
Repositories make it easy to install new software


**The four main repositories are:**


**Main** - Canonical-supported free and open-source software.
**Universe** - Community-maintained free and open-source software.
**Restricted** - Proprietary drivers for devices.
**Multiverse** - Software restricted by copyright or legal issues.


**Using apt**


**add-apt-repository** adds a **PPA** "**Personal Package Archives**" to your list of sources,
so that Ubuntu knows to look for updates from that PPA as well as from the official Ubuntu sources.


**sudo add-apt-repository ppa**:webupd8team/y-ppa-manager
**apt-get** update tells apt-get to update its database of
what packages can be installed and where to install them from.


**sudo apt-get update**


**apt-get** install causes apt-get to find the package in its database
and download and install the indicated file.


**sudo apt-get install y-ppa-manager**


**using dpkg**


**dpkg** is a package manager for Debian-based systems. It can install, remove, and build packages.
if you have a **.deb** file:


You can install it using **sudo dpkg -i /path/to/deb/file** followed by **sudo apt-get install -f**



**Uninstalling Programs with Terminal:**
## There are 2 ways to uninstall ubunto software

**1. First way using terminal**


**dpkg --list**   get the list of programs inastalled.

![IMG](https://www.wikihow.com/images/thumb/d/d4/Uninstall-Ubuntu-Software-Step-9-Version-3.jpg/aid1874252-v4-728px-Uninstall-Ubuntu-Software-Step-9-Version-3.jpg.webp)

**apt-get --purge remove program_name**


it's required enter your **root password**.


then confirm deletion by "**Y**" or "**yes**".


**2. second way**

**Open Ubuntu Software:** Its app icon resembles an orange suitcase with a white "A" on it.


**Click the Installed tab:** This computer-shaped tab is at the top of the Ubuntu Software window.



**Find the program that you want to uninstall:** Scroll through the list of installed programs until you arrive at the one that you want to uninstall, or type the name of an installed program into the search bar in the top-right corner of the window.


**Click Remove:** It's to the right of the program that you want to uninstall.


**Confirm the decision if prompted:** If asked to confirm, click Remove again, or click OK.
