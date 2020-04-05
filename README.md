# imx7sabre-board-platform Get Started 
Yocto Development with MCIMX7SABRE: SABRE Board for Smart Devices Based on the i.MX 7Dual Applications Processors.
This repo is based on FSL Community BSP 

## Prerequisite

Install `repo` tool

1. `$ mkdir ~/bin`
2. `$ curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > ~/bin/repo`
3. `$ chmod a+x ~/bin/repo`
4. `$ PATH=${PATH}:~/bin`

## Get BSP

1. `$ mkdir imx7sabre-board-platform`
2. `$ cd imx7sabre-board-platform`
3. `$ repo init -u https://github.com/prabhakar-patil/imx7sabre-board-platform -b master -m default.xml`
4. `$ repo sync`
