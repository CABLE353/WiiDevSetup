# WiiDevSetup
Automates the setup process for Wii development(As far as I understand it).

## How it Works:

This script first downloads the codeblocks ide from winget. It then proceeds to install other neccessary dependancies to download the other programs involved with Wii Homebrew Developement. The script uses winget to install git, and cURL to download devkitPro and install it and clone into GRRLIB. DevkitPro is the compiler, and GRRLIB has many usefull libraries. The provided zip file contains a demo project with which has a pre-configured codeblocks project file and directory for compiling, it is downloaded and extracted to your C drive. The objective is for any user with decent knowledge of IDE's and coding to be able to run this script and jump right into coding/compiling. NO BS!! NO INCOMPLETE OR COMPLICATED TUTORIALS!! This script aims to make this entire process run and play.

## Why?
No more will anyone that decide to start dipping into casual or serious Wii Homebrewing will be lost in the weeds of setting up their environment, and running the right makefiles. This intends to do what none of the other devs have done in the past 15+ years Wii Homebrewing has been around, and that is; to make it easier for a begginer to add their ideas and discoveries to the scene.

## What if devkitPro or something else updates:
I'll do my best to update the script when I can, but for now it should always work even if things update because it's just doing what a user would have to do in order to set this all up manually. In other words, it's being the end user for the end user to set up the environment.

## Instructions:
Download the WiiDevSetup.bat file and run it. If the DevkitPro installer dialogs pops up, just follow the dialog to install the Wii toolchains. When the installer dialogs are finished, the script will automatically continue to the next step. DevkitPro gives several options to choose from as it's built for compiling Homebrew for multiple Nintendo machines. I recomend simply choosing the Wii tools by having it as the only box checked. That way you only have to worry about 1 compiler toolchain and default library. This script only works for the Wii's compiler toolchain so that is another thing to consider🙃.

## BE SURE TO RUN THIS AS ADMIN!!
This script puts these required tools in the root of your C Drive, and if you don't run it as admin, it won't install the environment correctly.

## Enjoy!!
