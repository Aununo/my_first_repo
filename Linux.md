### Ubuntu

1. `sudo apt update` or `sudo apt-get update` and `sudo apt upgrade`
This command is used to update the Ubuntu system package list. In Linux, apt is the abbreviation of Advanced Package Tool, which is a package management tool used to install, upgrade and remove software packages. The update subcommand is used to download the latest package information, but does not install or upgrade the package itself.
The apt-get tool is an old tool, and apt is considered an enhancement to apt-get.

### kali

#### install kali linux in the virtual box (Windows)

1. download and install [virtual box](https://www.virtualbox.org/wiki/Downloads).
2. head over to the [kali linux](https://www.kali.org/get-kali/#kali-virtual-machines)
3. path`D:/ISO/Linux/kali-linux-2023.4-virtualbox-amd64`

#### run

1. default admin and password: kali & kali.
2. You can customize the size of window and fonts in terminal by
`File - Preference - Appearance - Font change - 20pt`
3. update the package index.
`sudo apt-get update`
4. ensure all installed packages are brought up to their latest versions.
`sudo apt-get upgrade`
5. tidy up and clear some space.
`sudo apt-get autoremove`
6. remove any downloaded packages that are no long needed.
`sudo apt-get clean`
7. clear the terminal.
`clear`
