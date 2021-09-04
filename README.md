# SlackBuild Package Manager (SBPM)

SlackBuild Package Manager (SBPM) is a shell script
that allow users to download and install packages
from http://slackbuilds.org.

## Dependencies
> This script does not resolve dependencies. You can
get all package dependencies running "sbpm info package-name"
command for install it manually.

## How to use
Download and extract this repository in your system, and add the "execute permission" to the script.
> chmod +x sbpm

### Run ./sbpm help to show the help menu

	 sbpm help 			 show this content
	 sbpm sync 			 sync package data from slackbuilds.org
	 sbpm info <package_name> 	 show package information
	 sbpm search <package_name> 	 search for a specific package
	 sbpm install <package_name> 	 install a package

